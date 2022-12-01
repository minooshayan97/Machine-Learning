The data is in the data.npz file (attached). This data was generated based on the following relationship:

$$ y = 4x_2^2x_1 + 2x_2^2 + 3x_1 + 1 $$

Therefore, the samples are [x2,x1] and their corresponding output is y. There are six one-dimensional arrays in the npz.data file, x2test, x1test, ytest, x2, x1, y. An example of accessing the y file array is as follows:

$$ a = np.load('data.npz')$$

$$ print(a['y'])$$

The ytest array is the desired output on the test data (x2test,x1test) and you compare your outputs with these values. Next, we want to check the regression in three cases:

* Linear regression
* 3rd degree polynomial regression
* Grade 5 polynomial regression

In all three cases, the cost calculation is a function of SSE.

a . Regression without regularization: Implement the three cases without the regularizer and compare the results on the test data. Use the closed linear/generalized linear regression formula to calculate w. Report the value of the loss function on the training data and test data for each of the three cases

b. Do part a using Descent Gradient.

Regression with regularization: In this section, add an L2 regularizer term with multiplier λ to the SSE cost function. Using Validation Cross Fold 5, find the best value of parameter λ among the members of the set, 10-3, 1,..., 10-4 in each case and then get the result on the test data.
