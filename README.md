# Bike Sharing Business
![bike](https://github.com/KuntamukkalaPavanKumar/Boom-Bikes/blob/main/blog_featured-image_milano.jpg)

## Abstract
The purpose of this project is to analyse the significant variables affecting Bike Sharing business of 'Boom Bikes' company.
For this project, we adopted Multivariate Linear Regression to determine those significant variables and made suggestions to increase the revenue of business post corona.

## Dataset
The data set contains 'cnt' as target variable, which represents number of bikes shared during different seasons.
The other variables are 'temperature', 'humidity', 'season', 'holiday', 'weekend'.

## Experimentation:
We cleaned the dataframe, by removing outliers and NaN values.
Then we converted the object columns to  numeric ones by using 'One Hot Encoding' technique.
We split the dataset in to train and test.
After Rescaling (Normalizing) all the variables, we used RFE (Recursive Feature Elimination) technique.
Using Recursive Feature Elimination from SciKit library, we selected significant variables among numerous varialbes given in the dataset.
Then we employed Multivariate Linear Regression model.
Using p-value, we dropped the insignificant variables one at a time and arrived at final model.

### Model Evaluation:
We acheived accuracy of 80% on test dataset using the Multivariate Linear Regression model.