# Linear Regression for Predicting Football Player Attacking Stats

## Introduction:
Linear regression is a statistical method used for modeling the relationship between a dependent variable and one or more independent variables. In this context, we use linear regression to predict a football player’s attacking stats based on various attributes such as finishing, heading accuracy, passing skills, etc.

## Step-by-Step Explanation:
1. **Data Loading and Preprocessing**:
   - The dataset containing football player statistics is loaded into a pandas DataFrame.
   - Basic data preprocessing is performed, which includes selecting relevant features (attributes) that will be used for predicting the attacking stats of the players.

2. **Simple Linear Regression with Single Feature**:
   - A simple linear regression model is created using 'Finishing' as the predictor (independent variable) and 'Attacking' as the target (dependent variable).
   - The dataset is split into training and testing sets to ensure that the model is trained on one subset and tested on another to evaluate its performance.
   - The model is trained on the training data and its performance is evaluated on the test data using the Mean Squared Error (MSE) metric.
   - The trained model is then used to predict the attacking stat for a new player based on their finishing stat.

3. **Visualization**:
   - The performance of the model is visualized by plotting the actual vs predicted values for the test data. A regression line is drawn to show the relationship between the finishing and attacking stats.

4. **Multiple Linear Regression with Multiple Features**:
   - The regression model is extended to include multiple features such as heading accuracy, short passing, long passing, dribbling, etc., to predict the attacking stat.
   - Missing values in the dataset are handled by imputing them with the mean value of the respective features.
   - The model is trained on the selected features and the target variable, and its performance is evaluated using Mean Squared Error.
   - Predictions are made for a new player by taking user input for multiple attributes and feeding them into the model.

5. **Interactive Prediction for Multiple Features**:
   - The user is prompted to enter various attributes (e.g., heading accuracy, short passing, long passing, etc.) for a new player.
   - The model then predicts the attacking stat for the player based on the input attributes.

6. **Model Evaluation Metrics**:
   - Several evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared are calculated to assess the performance of the model.
   - These metrics provide a comprehensive understanding of how well the model is performing in predicting the attacking stats.

7. **Model Accuracy Calculation**:
   - The accuracy of the model is calculated using the R-squared metric, which indicates how well the independent variables explain the variability in the dependent variable. This accuracy is expressed as a percentage to provide a clearer understanding of the model's predictive power.

## Conclusion:
The process demonstrates how to perform linear regression for predicting football player attacking stats based on various player attributes. It includes steps such as data loading, model creation, evaluation, visualization, and interactive prediction, providing a comprehensive approach to building and evaluating a predictive model in the context of sports analytics.
