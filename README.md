# Network Intrusion Detection

This project involves the classification of network traffic data. The data is preprocessed, explored, and then used to train various machine learning and deep learning models.

### Dataset
https://research.unsw.edu.au/projects/unsw-nb15-dataset

### Code Description

1. **Data Loading and Preprocessing**: Four CSV files are loaded, combined, and cleaned. This includes handling missing values, normalization, and encoding categorical features.

2. **Data Splitting**: The data is split into training, validation, and test sets.

3. **Model Training**: Several machine learning models (Logistic Regression, K-Nearest Neighbors, Decision Tree, Random Forest, XGBoost) are trained using GridSearchCV for hyperparameter tuning. A deep learning model is also trained using Keras.

4. **Model Evaluation**: The models are evaluated on the test data using metrics such as accuracy, precision, recall, and F1-score.

### Requirements

To run this code, install Python as well as the libraries used in the code: pandas, numpy, sklearn, seaborn, matplotlib, keras, and xgboost.
