# Credit Risk Analysis
## Overview
The purpose of the Credit Risk Analysis project was to analyze the balanced accuracy score and the precision and recall scores of six different machine learning models to determine which algorithm results in the best performance.

## Results
The following bullets describe the balanced accuracy score and the precision and recall scores of each machine learning model, organized by the type of model. 
#### __OVERSAMPLING__
##### Naive Random Oversampling
- The calculated balanced accuracy score of the naive random oversampling model was 0.65 (65%), and the precision and recall scores equated to 0.01 and 0.69, respectively.
<p align="center">
  <img src="https://github.com/kylegross/Credit_Risk_Analysis/blob/main/naive_random_oversampling.PNG" />
</p>

##### SMOTE Oversampling
- The calculated balanced accuracy score of the SMOTE oversampling model was 0.66 (66%), and the precision and recall scores equated to 0.01 and 0.63, respectively.
<p align="center">
  <img src="https://github.com/kylegross/Credit_Risk_Analysis/blob/main/SMOTE_oversampling.PNG" />
</p>

#### __UNDERSAMPLING__
##### Cluster Centroid Undersampling
- The calculated balanced accuracy score of the Cluster Centroid undersampling model was 0.54 (54%), and the precision and recall scores equated to 0.01 and 0.67, respectively.
<p align="center">
  <img src="https://github.com/kylegross/Credit_Risk_Analysis/blob/main/undersampling.PNG" />
</p>

#### __COMBINATION (OVER AND UNDER) SAMPLING__
##### Combination Sampling
- The calculated balanced accuracy score of the combination sampling model was 0.68 (68%), and the precision and recall scores equated to 0.01 and 0.78, respectively.
<p align="center">
  <img src="https://github.com/kylegross/Credit_Risk_Analysis/blob/main/combination_sampling.PNG" />
</p>

#### __ENSEMBLE LEARNERS__
##### Balanced Random Forest Classifier
- The calculated balanced accuracy score of the balanced random forest classifier was 0.79 (79%), and the precision and recall scores equated to 0.03 and 0.70, respectively.
<p align="center">
  <img src="https://github.com/kylegross/Credit_Risk_Analysis/blob/main/balanced_random_forest.PNG" />
</p>

##### Easy Ensemble AdaBoost Classifier
- The calculated balanced accuracy score of the easy ensemble AdaBoost classifier was 0.93 (93%), and the precision and recall scores equated to 0.09 and 0.92, respectively.
<p align="center">
  <img src="https://github.com/kylegross/Credit_Risk_Analysis/blob/main/AdaBoost_classifier.PNG" />
</p>

## Summary
The ensemble learner models significantly outperformed the oversampling, undersampling, and combination models, with the balanced random forest classifier and easy ensemble AdaBoost classifier equating to 79% and 93% balanced accuracy scores, respectively. As is evident, the AdaBoost classifier had the highest total accuracy score with a margin of about 14%. The least-accurate model was the Cluster Centroid undersampling model, which had a total accuracy score of 54%. Both of the oversampling models had similar accuracy scores at 65% and 66%, but they are not comparable to the AdaBoost classifier.
<p> The ensemble learners produced better results than the other models because multiple algorithms are used to learn and create predictions based on the data, with the final prediction based on the accumulated predictions from each algorithm. The ensemble learners combine multiple models to help improve the accuracy and decrease variance of the model, which thereby increases the model's overall performance. As such, it is recommended to use the ensemble models to predict the outcomes in future risk analyses. </p>
