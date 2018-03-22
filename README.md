# energy-efficiency-uci

The dataset was obtained from http://archive.ics.uci.edu/ml/datasets/energy+efficiency. The task is to predict the heating and cooling loads
from the given feature values which was experimented on different building shapes. The features are

X1 Relative Compactness  
X2	Surface Area  
X3	Wall Area  
X4	Roof Area  
X5	Overall Height   
X6	Orientation  
X7	Glazing Area   
X8	Glazing Area Distribution   
y1	Heating Load  
y2	Cooling Load  

For this particular problem decision trees and random forests worked pretty well. With decision trees the heating load(y1) was predicted with an accuracy
of nearly 99.5% and with Random Forests the cooling load(y2) was predicted with an accuracy of around 97%.
