Notes are taken from [machinelearningmastery](https://machinelearningmastery.com/) websit. 
# Machine Learning Key Ingredients:
+ Data (training, test, validation)
	+ Training data is used to defining the features (or parameters?)
	+ Test data would not be used until model is complete, and then we test the model with it
+ Model (Linear regression, Logistic regression, Neural network, Support vector machine, etc.)
+ Loss function 
	+ It determines how good the model is working
+ Optimization method


# Supervised Learning
Supervised learning technique uses labeled dataset to train (supervise) algorithms into classifying data or predicting outcomes accurately.
+ **Classification**:
	+Creating a predictive mapping function from input variables (x) to discrete output variables (y)
	    + If there are two classes (types or categories of output) it's called a binary classification
	    + If there a re more than two classes it's called multi-class classification
  + Uses an algorithm to accurately assign test data into specific categories, such as separating apples from oranges.
  + Or, in the real world, supervised learning algorithms can be used to classify spam in a separate folder from your inbox.
  + **Linear classifiers**, **support vector machines**, **decision trees** and **random forest** are all common types of classification algorithms

+ **Regression**:
	Another type of supervised learning method that uses an algorithm to understand the relationship between dependent and independent variables.
		○ It is about creating a predictive mapping function from input variables (x) to continuous output variables (y)
		○ Regression models are helpful for predicting numerical values based on different data points, such as sales revenue projections for a given business.
		○ Some popular regression algorithms are linear regression, logistic regression and polynomial regression.

	- **Classification vs Regression**: 
		○ Sometimes there's an overlap between classification and regression
			§ A classification algorithm may predict a continuous value, but the continuous value is in the form of a probability for a class label.
			§ A regression algorithm may predict a discrete value, but the discrete value in the form of an integer quantity.
		○ However, the way we evaluate classification and regression does not overlap and is unique:
			§ Classification predictions can be evaluated using accuracy, whereas regression predictions cannot.
Regression predictions can be evaluated using root mean squared error, whereas classification predictions cannot.![image](https://user-images.githubusercontent.com/79114383/174604691-fdf80c4a-b508-47be-beca-a811fdfa7a26.png)
