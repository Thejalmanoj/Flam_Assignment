# Flam_Assignment
Solution:
---------
$$
\left(t*\cos(28.12)-e^{0.0214\left|t\right|}\cdot\sin(0.3t)\sin(28.12)\+54.9012, 
42+t*\sin(28.12)
+e^{0.0214\left|t\right|}\cdot\sin(0.3t)\cos(28.12)
\right)
$$

Steps to solve the problem:
--------------------------
1. Data is given as an excel sheet with 2 columns x and y.
2. Read the file using pandas.
3. Generate values for t within the range, 6<t<60.
4. Define a function to predict a curve from test parameters and compute L1 distance.
5. Set range or boundaries for each parameter.
6. Save the results to a file and return the values.
