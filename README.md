**Phishing URL Classification Project**

**Overview**

This project aims to classify URLs as either phishing or legitimate using the PhiUSIIL Phishing URL Dataset. 
The classification model is built using XGBoost, with feature selection and hyperparameter tuning to improve performance.

**Dataset**

The dataset used in this project is the PhiUSIIL Phishing URL Dataset, 
which contains a variety of features extracted from URLs and their corresponding webpages

**Usage**

**Data Preprocessing**

Load the dataset and encode categorical features, in this case the TLD column. Other categorical columns were deleted.
Apply feature scaling and selection.

**Model Training**

Define the XGBoost model and parameter grid for hyperparameter tuning.
Perform grid search with cross-validation to find the best hyperparameters.
Train the model using the best parameters.

**Model Evaluation**

Evaluate the model using classification metrics such as accuracy, precision, recall, and F1-score.
Plot the ROC curve to visualize model performance.

**Results**

The model achieved an accuracy of 99.99% on the test set with a ROC-AUC score of 1.00. 
This indicates that the model is highly effective at distinguishing between phishing and legitimate URLs.

**Conclusion**
This project demonstrates how to build a robust phishing URL classification model using XGBoost with feature selection and hyperparameter tuning.
The high accuracy and ROC-AUC score indicate that the model can effectively identify phishing URLs, which can be valuable for cybersecurity applications.

**Future Work**
Experiment with other machine learning algorithms.
Further optimize feature selection and hyperparameter tuning.
Deploy the model as a web service for real-time URL classification.

**License**

This project is licensed under the MIT License - see the LICENSE file for details.
