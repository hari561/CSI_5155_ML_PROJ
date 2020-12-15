# CSI 5155 Machine Learning Project

This project involves the analysis of health care data, as obtainable from
https://archive.ics.uci.edu/ml/machine-learning-databases/00296/

Specifically, the dataset contains the information about patients with diabetes in 130 hospitals in the USA for the years 1999 to 2008. The study consists of approximately 100,000 patients with 50 features, some containing missing values.

Below are the tasks performed:

A: Feature engineering, supervised learning & evaluation of results

Task 1: The first task is to predict the outcomes, in terms of patient re-admissions. This is a multi-class learning problem, with three class labels {no, readmitted within 30 days, readmitted after 30 days}.

Task 2: The choice of the second task is your own. For instance, an angle would be to explore the data by using gender as class label. Alternatively, building models by using age ranges, or the admissions source, as class labels, could also provide us with additional insights.

Algorithms applied are:

K-NN with K=8
,Guassian Naive Bayes
,Bernoulli Naive Bayes
,SVM with linear kernel
,Decision Tree
,Random forest
,Extra Tree
,Bagging with decision tree

Also, Model metrics, results are shown in the form of classification report, confusion matrix, ROC curves


B: Semi-supervised learning & evaluation of results

tested various levels of unlabelled data, notably 0% (fully supervised - baseline), 10%, 20% 50%, 90% and 95% and displayed results and metrics in the form of classification report and confusion matrix

Algorithms applied/ tried are:

Label propagation
,Label spreading
,Particle comptetion and cooperation
,Naive Bayes
,K-NN


