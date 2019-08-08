# MachineLearningProject
CSCE 633 ML Project

Problem Objective
We define our problem to be : Using CGM (Continuous Glucose Monitoring)  to classify ( Binary classification, possibly tertiary classification) macronutrient composition of a meal consumed by a given individual. 

Problem Significance
Pre-diabetes and diabetes are currently a major health issue. Devices monitoring CGM signals are quite new in the market and thus these CGM signals need to be explored. 

A diabetic patient can’t always know or remember to keep track about the macronutrient composition of the their meals. Since CGM devices are an unobtrusive, cheap and reliable, it would be helpful for patients if there was an application utilising these CGM devices to keep track of their meal composition on a regular basis. 

Proposed Approach
We plan to use various supervised classification techniques to classify the macronutrient composition, such as : Logistic regression, decision trees, Random forests and SVM. 

For these techniques we will require informative features. The features we plan on using are : Max peak, half peak difference, tail part of the signal, auc, mean, sd, skewness, steepness of rise and fall, rise and fall slope. Apart for these classical feature extraction techniques,we want to extract features using sparse representation of CGM signals.

Evaluation
We will use Logistic regression as a baseline for our application. We will measure the performance of the system across various supervised classification techniques using industry specific measures such as :  f1-score, precision, recall, accuracy, correlation etc.

Data Description
For this application we are using the PLos dataset. This dataset comprises of CGM signals from 29 candidates monitored over 3 meals each. 


Expectations
We expect to get highly accurate macronutrient predictions based on an individual's CGM signal. We expect a few challenges during the course of this project , few challenges are that we have a limited data set, CGM signals are different than usual time series signals and thus difficult to evaluate, this also presents us with the problem of having less number of  features to built the classification model on.

