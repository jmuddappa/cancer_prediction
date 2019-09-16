# Tumor classifier

# Goal
To have a high precision classifier with as low false negatives as possible i.e. do not label malignant tumors as benign.

# Description
Jupyter notebook showing the development of a classifier used to predict whether a tumor is malignant or benign using numerical features.

# Conclusion
This notebook stars off with EDA into the features followed with using a baseline classifier of logistic regression. I also tried XGBoost due to it's simplicity and ability to capture non-linear information from the data. I found that the baseline model had very high precision and so I went ahead with predicting on the test data using that model.

In conclusion I developed a model that had a precision of 90%.
