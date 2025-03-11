# SalesProject
Retail Sales Analysis and Forecasting

Project Overview

This project focuses on analyzing retail sales data, forecasting future sales using Facebook's Prophet model, and segmenting customers using K-Means clustering. The dataset includes transactional data such as customer demographics, purchase details, and sales amounts.

Data Preprocessing

Loaded the dataset using pandas and converted the 'Date' column to datetime format.

Encoded categorical variables:

Converted 'Gender' to numerical values (Male = 1, Female = 0).

Dropped unnecessary columns ('Customer ID', 'Transaction ID').

Used one-hot encoding for the 'Product Category' column.

Ensured proper data types for categorical variables.

Exploratory Data Analysis (EDA)

Generated a correlation heatmap to identify relationships between variables.

Explored distribution and patterns in the sales data.

Sales Forecasting Using Prophet

Renamed columns to fit Prophet's requirements (ds for date, y for sales amount).

Trained a Prophet model to forecast sales for the next 30 days.

Visualized forecasted sales trends and model components.

Analyzed residuals to assess model performance.

Customer Segmentation Using K-Means Clustering

Applied the Elbow Method to determine the optimal number of clusters.

Clustered customers based on their age and purchase amounts.

Visualized clusters using a scatter plot with color-coded segments.

Predictive Modeling with Random Forest Regressor

Prepared features and target variables for prediction.

Split the data into training and testing sets.

Trained a RandomForestRegressor model to predict total sales amounts.

Evaluated model performance using the R² score.

Key Insights

Sales Forecasting: The Prophet model provides a reasonable prediction of future sales trends, helping in demand planning.

Customer Segmentation: K-Means clustering identifies distinct groups of customers based on their purchasing behavior, which can inform targeted marketing strategies.

Sales Prediction: The Random Forest model can help in predicting sales amounts based on customer demographics and purchase details.

Conclusion & Next Steps

This project demonstrates the application of machine learning techniques in retail analytics. Future enhancements may include:

Incorporating external factors (e.g., holidays, promotions) to improve sales forecasting.

Using advanced clustering techniques like DBSCAN for more flexible customer segmentation.

Hyperparameter tuning to improve the predictive performance of models.

This project highlights my ability to clean and analyze retail data, apply machine learning models, and derive business insights. It serves as a valuable addition to my portfolio, showcasing practical data science skills in forecasting, clustering, and predictive analytics.

