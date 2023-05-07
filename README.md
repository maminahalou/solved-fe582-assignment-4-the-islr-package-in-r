Download Link: https://assignmentchef.com/product/solved-fe582-assignment-4-the-islr-package-in-r
<br>
This question should be answered using the Weekly data set, which is part of the ISLR package in R. The file have been included in the assignment as <strong><em>Weekly.csv</em></strong>. It contains 1,089 weekly returns for 21 years, from the beginning of 1990 to the end of 2010.

<ol>

 <li>Produce some numerical and graphical summaries of the Weekly data. Do there appear to be any patterns?</li>

 <li>Use the full data set to perform a logistic regression with Direction as the response and the five lag variables plus Volume as predictors. Use the summary function to print the results. Do any of the predictors appear to be statistically significant? If so, which ones?</li>

 <li>Compute the confusion matrix and overall fraction of correct predictions. Explain what the confusion matrix is telling you about the types of mistakes made by logistic regression.</li>

 <li>Now fit the logistic regression model using a training data period from 1990 to 2008, with Lag2 as the only predictor. Compute the confusion matrix and the overall fraction of correct predictions for the held out data (that is, the data from 2009 and 2010). e) Repeat d) using LDA.</li>

 <li>Repeat d) using QDA.</li>

 <li>Repeat d) using KNN with K = 1.</li>

 <li>Which of these methods appears to provide the best results on this data?</li>

 <li>Experiment with different combinations of predictors, including possible transformations and interactions, for each of the methods. Report the variables, method, and associated confusion matrix that appears to provide the best results on the held out data. Note that you should also experiment with values for K in the KNN classifier.</li>

</ol>

<strong>Problem 2</strong>

In this problem, you will develop a model to predict whether a given car gets high or low gas mileage based on the <strong><em>Auto.csv</em></strong> data set.

<ol>

 <li>Create a binary variable, mpg01, that contains a 1 if mpg contains a value above its median, and a 0 if mpg contains a value below its median. You can compute the median using the median() function. Note you may find it helpful to use the data.frame() function to create a single data set containing both mpg01 and the other Auto variables.</li>

 <li>Explore the data graphically in order to investigate the association between mpg01 and the other features. Which of the other features seem most likely to be useful in</li>

</ol>

predicting mpg01? Scatterplots and boxplots may be useful tools to answer this question. Describe your findings.

<ol>

 <li>Split the data into a training set and a test set.</li>

 <li>Perform LDA on the training data in order to predict mpg01 using the variables that seemed most associated with mpg01 in b). What is the test error of the model obtained?</li>

 <li>Perform QDA on the training data in order to predict mpg01 using the variables that seemed most associated with mpg01 in b). What is the test error of the model obtained?</li>

 <li>Perform logistic regression on the training data in order to predict mpg01 using the variables that seemed most associated with mpg01 in b). What is the test error of the model obtained?</li>

 <li>Perform KNN on the training data, with several values of K, in order to predict mpg01. Use only the variables that seemed most associated with mpg01 in (b). What test errors do you obtain? Which value of K seems to perform the best on this data set?</li>

</ol>