# Classify-Handwritten-Images

This project involves classifying each of the images in a dataset of handwritten images to see their categories if they belong to the digits 0 to 9. The Random Forest algorithm was used.

A random forest is a collection of decision trees whose results are aggregated into one final result. It creates several decision trees and aggregates the final results. In doing this, the dataset is randomly split into several samples (hence the name "random") and a decision tree is built for each sample, resulting into several trees (hence the name "forest").

The ability of random forests to limit overfitting without increasing error due to bias is why they are so powerful.

One way that random forests reduces errors due to variance and bias is by training on different samples of the data. A second way is by using a random subset of features in each decision tree model, e.g. 10 per decision tree model out of a total of 50 features/columns/variables in a dataset.

Random forest is a supervised ML model. One of the biggest advantages of random forest is its versatility. It can be used for both regression (wherein the target variable is numeric and continuous) and classification tasks (wherein the target variable is categorical), and it's also easy to view the relative importance it assigns to the input features.

In this project, we will be using the Random Forest algorithm for a multinomial classification problem.

## Dataset Description
The digits dataset from sklearn was used. This dataset is made up of two sub-datasets - a digits.data (containing only predictor variables/features) and a digits.target (containing only the target variable).

## Tools/Applications/Softwares/Packages Used for the Project
The python programming language, along with libraries such as Sci-kit learn, pandas, numpy, Seaborn and matplotlib, was used for the explorations and visualizations contained in this work.

## Key Insights for Analysis/Investigation
In this project, I endeavoured to find out how accurately a trained ML model can identiy the digits 0 to 9 written with free hands.

## Summary of Findings
The model accuracy of 0.96 or 96% shows that ML models can indeed perform well with adequate training.

We could adjust the n_estimators parameter (number of trees) and would arrive at a different score or accuracy. This would be especially necessary if we got a low score value, in which case we would continue adjusting the n_estimators value until we arrive at a desired result.
