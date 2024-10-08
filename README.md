# Automating the Dry Beans Classification Process
# Aim
1)	To use data mining techniques to automate the process of grading and classifying dry beans
2)	To use two classification algorithms on the data set, evalaute each algorithm performance and consider other methods of improving performance
# Data Set
The dry beans data set used for this work was obtained from the uci machine learning repository [here](https://archive.ics.uci.edu/ml/machine-learning-databases/00602/)
There are seven distinct classes for the class label. This implies that observations were made for seven different types of dry beans. In all, there are 13,611 observations, 
with 17 different features (including the class label). This means there are 16 independent variables and a single dependent variable (the class label) that has 7 distinct classes 
thus making it a multiclass classification problem. The data set features information is given below.

1) Area (A): The area of a bean zone and the number of pixels within its boundaries.
2) Perimeter (P): Bean circumference is defined as the length of its border.
3) Major axis length (L): The distance between the ends of the longest line that can be drawn from a bean.
4) Minor axis length (l): The longest line that can be drawn from the bean while standing perpendicular to the main axis.
5) Aspect ratio (K): Defines the relationship between L and l.
6) Eccentricity (Ec): Eccentricity of the ellipse having the same moments as the region.
7) Convex area (C): Number of pixels in the smallest convex polygon that can contain the area of a bean seed.
8) Equivalent diameter (Ed): The diameter of a circle having the same area as a bean seed area.
9) Extent (Ex): The ratio of the pixels in the bounding box to the bean area.
10) Solidity (S): Also known as convexity is the ratio of the pixels in the convex shell to those found in beans.
11) Roundness (R): Calculated with the following formula: (4piA)/(P^2)
12) Compactness (CO): Measures the roundness of an object: Ed/L
13) ShapeFactor1 (SF1)
14) ShapeFactor2 (SF2)
15) ShapeFactor3 (SF3)
16) ShapeFactor4 (SF4)
17) Class (Seker, Barbunya, Bombay, Cali, Dermosan, Horoz and Sira)
# 
