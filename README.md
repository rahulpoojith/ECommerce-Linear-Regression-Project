This dataset is having data of customers who buys clothes online. The store offers in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.

The company is trying to decide whether to focus their efforts on their mobile app experience or their website.



Steps Involved
1) Reviewing the Dataset
* Read the Dataset and review the dataset colums
* Reviewing the datatypes for each column
* Reviewing statiscal information for each of the variables

2) Exploratory Data Analysis
We begin by asking: How is the time clients spend on each platform related to their annual spending? The data reveals little to no correlation between the time spent on the desktop website and the amount clients spend per year. In contrast, the second graph shows a slight positive correlation between time spent on the mobile app and yearly spending. This could be due to clients spending less time browsing on the app, possibly because the payment process is quicker or the calls-to-action are more effective.
Upon analyzing the pairplot, we observe one significant positive correlation: the length of membership and yearly expenditure. To better illustrate this, we recreate the plot and include the regression line for clearer visualization of this relationship.
* Check time on website vs yearly amont spent
* Check time on app vs yearly amount spent
* Now let's compare all variables at the same time

3) Splitting the Data and making the model learn the data
X are the predictores, and y is the output. What we want to do is create a model that will take in the values in the X variable and predict y with a linear regression algorithm. We will use the SciKit Learn library to create the model.
* Taking all of the data, dividing it into a training set and a testing set
* defining each variable by train/test split
* importing machine learning model library
* fitting/training data:
* running columns as observations & one column for the coefficient (Note: The higer coefficient = more important)

4) Predictions
* giving values for x, using the X-test
* visualizating predictions (x-axis) and actual y values (y-axis)

5) Evaluation of Models using Metrics
* Importing MSE, MAE, R2 Score from scikit-learn for model evaluation and math for additional calculations
* calculating residuals: difference between actual values (y_test) and predicted values (predictions)
* visualizing the distribution of residuals with 20 bins and a Kernel Density Estimate (KDE) curve using seaborn
