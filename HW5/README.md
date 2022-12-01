#HW5
## Instructor : Dr.babaali
### The first question
In this exercise, you work with csv.HW5 data set. The Income feature is a dependent feature.
1. Specify the columns that have a numerical value and the columns that have a string value.
2. Check how many empty cells each column has.
3. Provide a method to deal with cells with missing values and briefly explain it. Subsequent queries should be performed using the edited version of the dataset, which does not contain the empty value.
4. If we have a model that always outputs the value of Income class less than 50 thousand dollars, how accurate will it be? We consider this model as Baseline.

### The second question
We intend to use the linear regression classifier 2 for classification.
1. Before using linear regression, do the necessary pre-processing on the data set you obtained from the previous section (the data set that does not have empty values), and briefly explain what you did.
2. Report the performance of linear regression using Cross Validation with a value of CV = 10.

### The third question
We intend to use simple Bayes classification for classification.
1. Before using Simple Bayes, do the necessary pre-processing on the data set you obtained from question one (the data set that does not have empty values), and briefly explain what you did.
2. Report the simple Bayes function using Cross Validation with a value of CV = 10.
3. Explain what distribution the library you use or the code you wrote yourself considers in relation to each feature.
The fourth question
Compare the results of 3 built models, Baseline model, linear regression model and simple Bayes model.
