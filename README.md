# Linear_Regression_Generalized
The aim of this project was to create a code that could perform linear regression for data of all sizes. The user just needs to upload the data with labels and a linear regression of the data is done.

There are two codes that have been uploaded for this purpose (along with an example data file (HousePricing.txt)
1. Linear Regression with Vectorized Gradient Descent
2. Linear Regression with scipy.optimize.minimize

The code for linear regression with gradient descent allows you to visualize the change in your cost/error function value over iterations. On the other hand, the code with scipy.optimize.minimize provides you the cost/error function value before and after miniminzation.

The method of optimization in the code with scipy can be changed based on the type of data that is being analysed.

It is important to ensure that all features are arranged column wise, with the 'y' data in the last column, and all the features are labelled.

The code prints out the values of the parameters at the end (stored in theta), and allows you to input new data to get a new predicted value.

The code only performs linear regression using a first degree model. A more generalized code that will offer higher degrees of the model is being worked on.
