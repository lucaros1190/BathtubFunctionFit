# BathtubFunctionFit
Python script to estimate the parameters of a fourth polynomial function. This function is usually used to interpolate data about the dependence of the mortality on temperature in ectotherms population modelling

# How to use this script:

Insert the values into the data.txt file considering the first column as the 'x' variable, the second column as the 'y' variable, 
the third column as the error associated to 'x', namely 'x_err', and the fourth column as the error associated to 'y', namely 'y_err'.

If you have doubts, please refer to the data.txt file filled into this repository. Remember to separate the columns with a 'tab' space!

# How to run the script:

Open a terminal and type

    python3 fitmort.py

If you need to change the plot range or the initial values for the regression, please open the file fitmort.py and change the dedicated 
section accordingly.
