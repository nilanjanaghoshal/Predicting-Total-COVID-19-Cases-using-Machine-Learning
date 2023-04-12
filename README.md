# Predicting-Total-COVID-19-Cases-using-Machine-Learning
Analyzing COVID-19 data for different countries
The Python script is analyzing COVID-19 data for different countries. The script loads the data from an online source, checks for missing values, converts the date column to datetime format, and adds columns for the total number of cases and the log of the total number of cases. It then performs some exploratory data analysis, including a scatter plot of the log of total cases per capita vs time, a bar plot of total cases by country, and a heatmap of the correlation matrix.

After the exploratory data analysis, the script creates X and y variables, scales the data using StandardScaler, and splits it into training and testing sets. It then fits two regression models to the data: Ridge Regression and Random Forest Regression.

The script reports the R2 score and the mean squared error (MSE) for each model. The R2 score for both models is 1.0, indicating that they fit the data perfectly. However, the MSE value of 6382.0889 for Ridge Regression and 340671264.3615 for Random Forest Regression suggest that the Ridge Regression model is a better fit for the data.

Overall, the Python script is trying to predict the total number of COVID-19 cases using confirmed, recovered, and death cases as independent variables. The script performs exploratory data analysis and compares two regression models to determine which model is a better fit for the data.
