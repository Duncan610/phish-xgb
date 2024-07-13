**PHISHING URL DETECTION PROJECT**

## Table of Contents

1. [Dataset Source](#dataset-source)
2. [Project Title](#project-title)
3. [Project Description](#project-description)
4. [Introduction](#Introduction)
5. [Data Preprocessing](#data-preprocessing)
6. [Model training](#Model-training)
7. [Model Evaluation](#Model-evaluation)
8. [Results](#Results)
9. [Conclusion](#Conclusion)
10. [Known Issues](#known-issues)
11. [Conclusion and License](#conclusion-and-license)


**Dataset Source**

The dataset used in this project is the PhiUSIIL Phishing URL Dataset from the UCI Machine Learing Repository,
which includes 134,850 legitimate and 100,945 phishing URLs. 

**Project Title**

**PhiUSIIL Phishing URL (Website)**

**Project Description**

This project aims to accurately classify URLs as either phishing or legitimate by leveraging machine learning techniques and feature extraction from the URL and its corresponding webpage.

**Introduction**

Phishing is a prevalent cyber threat that can lead to significant financial losses and privacy breaches. This Phishing URL Detection project is designed to help mitigate such threats by providing a reliable tool to identify phishing URLs. Utilizing advanced machine learning algorithms, this project examines various features extracted from URLs and web pages to determine their legitimacy. This project is an essential resource for cybersecurity professionals, web administrators, and anyone concerned about online security.

**Data Preprocessing**

Load the dataset and encode categorical features, in this case the TLD column. Other categorical columns were deleted.
Apply feature scaling and selection.

**Model Training**

Define the XGBoost model and parameter grid for hyperparameter tuning.
Perform grid search to find the best hyperparameters.
Train the model using the best parameters.

**Model Evaluation**

Evaluate the model using classification metrics such as accuracy, precision, recall, and F1-score.
Plot the ROC curve to visualize model performance.

**Results**

The model achieved an accuracy of 99.99% on the test set with a ROC-AUC score of 1.00. 
This indicates that the model is highly effective at distinguishing between phishing and legitimate URLs.

**Conclusion**
This project demonstrates how to build a robust phishing URL classification model using XGBoost with feature selection and hyperparameter tuning.
The high accuracy and ROC-AUC score indicate that the model can effectively identify phishing URLs, which can be valuable for cybersecurity applications,
though continuous improvements are necessary.

**Future Work**
Experiment with other machine learning algorithms.
Further optimize feature selection and hyperparameter tuning.
Deploy the model as a web service for real-time URL classification.

**Known issues**

Although this project achieves a high accuracy of 99.99% and a perfect ROC curve of 1, it is still ongoing. Known issues include:

***Potential overfitting due to the high accuracy.***

***Need for more diverse datasets to improve generalizability.***

***Occasional false positives and false negatives.***

***I am actively working on addressing these issues and improving the model's robustness.***

**License**
This project is licensed under the MIT License. See the LICENSE file for more information.

