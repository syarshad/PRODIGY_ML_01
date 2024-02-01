In this project, a machine learning regression model was developed to predict house prices based on various features such as lot area, number of bathrooms, number of bedrooms, etc. The dataset used for this analysis contains information about houses including their features and corresponding sale prices.

## Methods Used:

## Data Collection: The dataset was obtained from Kaggle using the opendatasets library. This dataset contains a comprehensive set of features related to houses.

## Data Preprocessing:
Irrelevant columns were excluded from the dataset to focus on relevant features for predicting house prices.
Duplicated rows were removed to ensure data integrity.
Outliers in the features and target variable were identified and treated using the Interquartile Range (IQR) method to improve the robustness of the model.

## Exploratory Data Analysis (EDA):
A correlation matrix was generated and visualized using a heatmap to understand the relationships between features and the target variable.
Scatter plots were created to visualize the relationship between LotArea and SalePrice.

## Model Building:
The dataset was split into training and testing sets using an 80-20 split.
A Linear Regression model was instantiated and trained using the training data.

## Model Evaluation:
The trained model was used to make predictions on the testing data (X_test).
The coefficient of determination (R-squared) was calculated to evaluate the performance of the model.
A scatter plot was generated to visually assess the alignment between actual and predicted values of house prices.

## Results:
The linear regression model achieved an R-squared value of approximately 0.48489, indicating that the model explains around 48.49% of the variance in house prices based on the selected features.
