# Comparative-analysis-on-abalone-and-wine

## Overview
This project focuses on representation learning, parameter tuning, and classification comparisons using various machine learning algorithms. PCA and LDA have been employed for feature extraction, and classification has been performed using Naive Bayes, Decision Trees, Random Forests, and Gradient Tree Boosting, and a comparative analysis has been performed on the results. 

## Dataset
The project uses two datasets: Abalone and Wine.

## Task 1: Representation Learning
PCA was performed on each dataset to extract features, and the results were analyzed to determine the total variance explained by the principal components. The first two principal components were visualized using distinguishable colors and markers to represent the labels of each data point. Additionally, a scree plot was created to demonstrate the cumulative variance represented by the PCA eigenvectors. The accuracy of the KNN classifier was evaluated using the PCA features for different numbers of dimensions. A comparison was made between the obtained accuracy and the accuracy from KNN classification using original features. The t-SNE method was also employed to visualize the datasets in a 2D plot, and any observed patterns were analyzed.

## Task 2: Naive Bayes Classifier
Multinomial Naive Bayes and Complement Naive Bayes were compared using 5-fold cross-validation on all six datasets (including both the original and reduced dimensionality datasets). The accuracy of each classifier was calculated, and analysis and plots were provided to highlight any interesting issues or variants of Naive Bayes. 

## Task 3: Decision Trees Classifier
The best settings for classification on each dataset were determined using 5-fold cross-validation and a range of parameter values, focusing on the maximum depth of trees. The mean accuracy was plotted against the tree depth, and the results were interpreted. The resulting splitting rules used for the trees were examined to identify any interesting patterns or explanations. 

## Task 4: Random Forest Classifier
The best settings for classification on each dataset were determined using 5-fold cross-validation and a range of parameter values, considering the maximum depth of trees and the number of trees. The mean accuracy was plotted against the parameter settings (individually or using a heat plot). Individual tree plots or exports were not produced. 

## Task 5: Gradient Tree Boosting
Gradient Tree Boosting was employed for the classification of the datasets. Appropriate parameter settings were chosen based on judgment and experience with other methods. The model was trained, and its performance was analyzed and compared to that of Random Forests in terms of accuracy and runtime. 

## Task 6: Final Results
The pipeline that resulted in the best overall classification accuracy or the best accuracy for each dataset was discussed.
The effect of dimensionality reduction on different algorithms was analyzed, highlighting why certain algorithms may benefit more than others.
A results table was provided, summarizing the final accuracy scores for all six datasets.




