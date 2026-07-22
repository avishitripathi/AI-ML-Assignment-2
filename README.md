# Customer Churn Prediction using Logistic Regression

## Objective

The objective of this project is to develop a Machine Learning model using Logistic Regression to predict whether a telecommunications customer is likely to churn based on demographic information and service usage.

## Dataset

The project uses the Telco Customer Churn Dataset available on Kaggle.

Dataset Link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The dataset has not been uploaded to this repository.

## Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Methodology

The following steps were performed:

1. Loaded the Telco Customer Churn dataset using Pandas.
2. Explored the dataset and identified numerical and categorical features.
3. Identified `Churn` as the target variable.
4. Checked and handled missing values in the dataset.
5. Removed the `customerID` column as it is only an identifier.
6. Encoded the categorical variables using one-hot encoding.
7. Split the dataset into 80% training data and 20% testing data.
8. Built and trained a Logistic Regression model.
9. Predicted customer churn on the test dataset.
10. Evaluated the model using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

## Results

The Logistic Regression model was evaluated using the following metrics:

* Accuracy: 80.34%
* Precision: 65.20%
* Recall: 55.61%
* F1-Score: 60.03%

The confusion matrix is available in the `Assignment-2.ipynb` notebook.

The model provides a useful baseline for predicting customer churn. The evaluation metrics help measure how effectively the model identifies customers who are likely to leave the telecommunications service.

## Conclusion

The project demonstrates the use of Logistic Regression for customer churn prediction. Data preprocessing, categorical encoding, and appropriate train-test splitting were performed before training the model. Factors such as contract type, tenure, monthly charges, internet service, and payment method may influence customer churn. Logistic Regression provides a simple and interpretable baseline model; however, its assumption of a linear relationship may limit its ability to capture complex non-linear patterns in customer behavior.

## Project Files

* `Assignment-2.ipynb` – Complete Jupyter/Google Colab notebook containing data analysis, preprocessing, model training, evaluation, and conclusion.
* `README.md` – Project documentation.
