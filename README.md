📈 Ice Cream Revenue Prediction using Simple Linear Regression
This project demonstrates a basic machine learning workflow to predict ice cream revenue based on temperature using Simple Linear Regression in Python.

🔍 Context
The dataset used (Ice Cream.csv) contains records of temperature and corresponding ice cream revenue. This linear relationship is ideal for applying a regression model to understand and predict sales patterns.

🧠 What the Code Does
Data Loading: Imports the dataset from an online source using pandas.

Feature & Target Definition: Selects 'Temperature' as the independent variable (X) and 'Revenue' as the dependent variable (y).

Train-Test Split: Splits the data into training (70%) and testing (30%) sets.

Model Selection: Uses LinearRegression from scikit-learn.

Model Training: Fits the model on training data.

Prediction: Predicts revenue on the testing data.

Evaluation: Evaluates the model using MAE, MAPE, and MSE metrics.

🧪 Tech Stack
Python

Pandas

scikit-learn

📊 Key Learnings
How to perform regression with a single feature.

Importance of evaluating model performance with multiple metrics.

Basics of train-test split for generalization.# Ice-Cream-Revenue-Prediction
