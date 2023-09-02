
# Credit Card Default Prediction

## Objective

The objective of this project is to use Supervised Learning techniques to build a model capable of predicting whether a given credit card user will default on their payments next month.

## Background Information

A credit card is a financial instrument that allows users to borrow money from a bank for making purchases. Typically, these loans are for small amounts and are expected to be paid back on a short-term basis. When a credit card user fails to make their payments on time, it is considered a default.

For banks and financial institutions, it is crucial to predict how many people and who among their credit card users are likely to default. This information is essential for optimizing financial strategies and, if possible, mitigating the risks associated with defaults.

Therefore, for a bank that prioritizes financial safety, accurately identifying potential defaulters is of utmost importance.

## The Dataset

The dataset used in this project contains the following features:

- **Customer ID**: A unique customer identifier ranging from 1 to 1600.
- **Credit Limit**: The credit limit assigned to the customer.
- **Gender**: Customer gender.
- **Education**: Customer education level.
- **Marriage Status**: Customer marital status.
- **Age**: Customer's age.
- **Bill_Amount1**: Customer's credit card bill amount from 1 month ago.
- **Bill_Amount2**: Customer's credit card bill amount from 2 months ago.
- **Bill_Amount3**: Customer's credit card bill amount from 3 months ago.
- **Pay_Amount1**: The amount the customer paid 1 month ago.
- **Pay_Amount2**: The amount the customer paid 2 months ago.
- **Pay_Amount3**: The amount the customer paid 3 months ago.
- **Default payment next month**: A binary indicator (1 or 0) representing whether the customer will default on their payment next month.

**Total Rows**: 1600
**Features**: 12

**Target**: Default payment next month: 1 means default (customer will not pay the bill), 0 means non-default (customer will pay the bill)

## Fundamentals

The project uses several Python libraries for data manipulation, preprocessing, modeling, and evaluation. Some of the key libraries include:

- `pandas` and `numpy` for data handling and manipulation.
- `seaborn` and `matplotlib` for data visualization.
- `scikit-learn` for data preprocessing, model building, and evaluation.
- `imblearn` for addressing class imbalance in the dataset.

## Preprocessing

- Data preprocessing involves techniques such as feature scaling, encoding categorical variables, and handling class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).

## Models

A variety of supervised learning models are explored in this project, including:

- Random Forest Classifier
- Extra Trees Classifier
- HistGradientBoosting Classifier
- Gradient Boosting Classifier
- AdaBoost Classifier
- Logistic Regression
- Ridge Classifier
- Perceptron
- Decision Tree Classifier
- K-Nearest Neighbors Classifier
- Support Vector Classifier
- Gaussian Naive Bayes
- Dummy Classifier (for baseline comparison)

A SkLearn Pipeline is used to test all these models.

## Tuning

Hyperparameter tuning is performed using GridSearchCV to optimize the performance of selected models.

## Metrics and Evaluation

The project utilizes various evaluation metrics, including balanced accuracy, recall, precision, F1-score, and confusion matrices, to assess the performance of the models.

## License

This project is licensed under the MIT License 



