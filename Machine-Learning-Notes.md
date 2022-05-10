# Machine Learning

## Table of Contents
- [Machine Learning](#machine-learning)
  - [Table of Contents](#table-of-contents)
- [Machine Learning](#machine-learning-1)
  - [Arthur Samuel](#arthur-samuel)
  - [What is Machine Learning?](#what-is-machine-learning)
  - [Machine Learning Types](#machine-learning-types)
  - [Terminology](#terminology)
- [Machine Learning Process](#machine-learning-process)
- [Supervised Learning](#supervised-learning)
- [Unsupervised Learning](#unsupervised-learning)
- [Linear Regression Theory](#linear-regression-theory)
- [Residuals](#residuals)
- [Regression Error Metrics](#regression-error-metrics)
    - [MAE](#mae)
    - [MSE](#mse)
    - [RMSE](#rmse)
- [Scikit-learn and ML](#scikit-learn-and-ml)
- [Bias-Variance Trade-Off](#bias-variance-trade-off)
    - [Underfitted](#underfitted)
    - [Good Fit](#good-fit)
    - [Overfitted](#overfitted)


- Types of ML
- Input-Features-Independent Variables
- Target-Desired Output-Dependent Variables-Labels
- Observations-Samples
- Why do we need linear regression?
- Terms of correlation & regression
- Simple & multiple linear regression
- Residue minimization techniques(LSE, Gradient Descent)
- Evaluation Metric: R_Square(R^2)
- Residuals 
- Regression Error Metrics
- Scikit-learn and ML
# Machine Learning
## Arthur Samuel
Machine learning was defined in 1959 by Arthur Samuel. Professor Samuel was an employee of artificial intelligence at IBM, and he developed a program that could play chess better than a person. The Samuel Checkers-playing Program was among the world's first successful self-learning programs, and as such a very early demonstration of the fundamental concept of artificial intelligence (AI). He received a master's degree in Electrical Engineering from MIT in 1926, and taught for two years as instructor. In 1928, he joined Bell Laboratories, where he worked mostly on vacuum tubes, including improvements of radar during World War II. Samuel went to IBM in 1949, where he would conceive and carry out his most successful work. He is credited with one of the first software hash tables, and influencing early research in using transistors for computers at IBM. At IBM he made the first checkers program on IBM's first commercial computer, the IBM 701. The program was a sensational demonstration of the advances in both hardware and skilled programming and caused IBM's stock to increase 15 points overnight. He was known for writing articles that made complex subjects easy to understand. He was chosen to write an introduction to one of the earliest journals devoted to computing in 1953

>Machine Learning is a field of study that gives computer the ability without being explicitly programmed. -Arthur Samuel

## What is Machine Learning?
Machine learning is a data analytics technique, that gets computers to learn and also act like a human. Machine learning algorithms use computational methods to “learn” by feeding data and information. And it is also known as a field of data analytics to make predictions depending on trends and insights of the data. It is seen as a part of artificial intelligence. Machine learning algorithms build a model based on sample data, known as training data, in order to make predictions or decisions without being explicitly programmed to do so. Machine learning algorithms are used in a wide variety of applications, such as in medicine, email filtering, speech recognition, and computer vision, where it is difficult or unfeasible to develop conventional algorithms to perform the needed tasks.

## Machine Learning Types 
![ml](types-of-ML.jpg)

## Terminology
**Observations:** Each row in a dataset represents an observation.\
**Features:** Features are also sometimes referred to as “variables” or “attributes.” Each column except the label column in a dataset is called a feature.Values are independent.\
**Labels:** The features are the input and the label *(target)* is the output. Ex: spam or not spam email, price of the house. The value that is to predict. Values are dependent\
**Classification:** Each observation throws a category/class assignment.Classes are discrete (not numbers). Ex: spam / not spam.

# Machine Learning Process
1 - Data Aquisition\
2 - Data Cleaning\
3 - Test Data or Model Training & Building\
4 - Model Testing\
5 - Go Back to 3rd Step or Model Deployment

# Supervised Learning
It is the process of learning from labeled observations. Labels teach the algorithm how to label the observations. Majority of practical machine learning models use supervised learning. 

# Unsupervised Learning
It is the process of learning from unlabeled observations. It uses machine learning algorithms to analyze and cluster unlabeled datasets. These algorithms discover hidden patterns or data groupings without the need for human intervention. Theres no training for unsupervised learning.


>The main difference between supervised and unsupervised learning: Labeled data. The main distinction between the two approaches is the use of labeled datasets. To put it simply, supervised learning uses labeled input and output data, while an unsupervised learning algorithm does not.

# Linear Regression Theory
The correlation summarizes the direction of the association between two quantitive variables and the strenght of its linear trend.
direction of the correlation:

# Residuals
Sum and min of the residuals are always zero. Residuals are normally distributed for suitable linear regression.
# Regression Error Metrics
### MAE
### MSE
### RMSE
# Scikit-learn and ML
1 Import
2 Split data 
3 Model Building and Fit
4 Prediction
5 Evaluation

# Bias-Variance Trade-Off
### Underfitted
- A simple model with too few parameters may cause underfitting (high bias but low variance).
### Good Fit
### Overfitted




