# Supervised Machine Learning

In this project a machine learning maodel was developed to determine the percentage of a student based on the number of study hours.<br><br>

## Dataset <br>

Displaying the first 5 rows of the dataset <br><br>
![](./images/dataset.PNG)<br><br>

### Analysing the dataset <br><br>

![](./images/dataset_desc.PNG) <br><br>

### Checking for any null value in the dataset <br><br>

![](./images/check_notnull.PNG) <br><br>

### Understanding the relationship between "Hours" and "Scores" <br><br>

![](./images/relation_graph.PNG) <br><br>

From the above graph it can be observed that "Hours and "Scores" have linear relationship.<br>
Hence, a simple linear regression model can be trained for predicting the percentage of a student based on the number of hours of study.<br><br>

### Linear regression model on test data <br><br>

![](./images/prediction.PNG) <br><br>

### Regression line <br><br>

![](./images/regressionline.PNG) <br><br>

The accuracy for the above model is, <br>
RMSE - 4.65<br>
On Test data - 0.94<br>
On training data - 0.95<br>

From the accuracy scores obtained it can be observed that the model is overfitting the dataset little bit but the overall performance of the model is acceptable.
