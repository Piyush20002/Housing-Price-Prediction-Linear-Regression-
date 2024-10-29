# Housing-Price-Prediction-Linear-Regression-
Housing Price Prediction ( Linear Regression )

Key Concepts and Challenges:

1. Data Collection: Obtain a dataset with numerical features and a target variable for prediction. 
2. Data Exploration and Cleaning: Explore the dataset to understand its structure, handle missing values, and ensure data quality. 
3. Feature Selection: Identify relevant features that may contribute to the predictive model. 
4. Model Training: Implement linear regression using a machine learning library (e.g., ScikitLearn). 
5. Model Evaluation: Evaluate the model's performance on a separate test dataset using metrics such as Mean Squared Error or R-squared. 
6. Visualization: Create visualizations to illustrate the relationship between the predicted and actual values. 



Project Summary: Housing Price Prediction (Linear Regression)

Objective:

The primary objective of this project was to predict housing prices based on various features of the houses, such as area, number of bedrooms, bathrooms, and other amenities.

Process Overview

Data Loading and Exploration: The dataset was loaded from a CSV file containing 545 entries with 13 features related to housing.
Key columns included price, area, bedrooms, bathrooms, and several categorical variables like mainroad, guestroom, basement, etc.

Data Cleaning:
Missing Values: Checked for missing values, confirming there were none.
Outlier Detection: Used box plots and the Interquartile Range (IQR) method to identify outliers in the price variable. Detected outliers were printed for further inspection.
Feature Selection: Selected relevant features for analysis and model training, focusing on both numerical and categorical data.

Data Transformation:
Categorical variables were converted into numeric format using Label Encoding to prepare for model training.
Summary statistics and correlation matrices were generated to understand the relationships between features.

Data Splitting:
The dataset was split into training (80%) and testing (20%) subsets to evaluate model performance.
Model Training: Linear Regression Model was trained using the training dataset.
Coefficients for each feature were calculated, indicating their impact on the housing price.

Model Prediction: The model was used to predict prices on the test set, and results were compared with actual prices using scatter plots and regression plots.

Model Evaluation:

Calculated performance metrics: Mean Squared Error (MSE): 1,771,751,116,594.04
Root Mean Squared Error (RMSE): 1,331,071.42
R-squared Score: 0.65, indicating that approximately 65% of the variance in housing prices was explained by the model.

Key Insights

Feature Importance: 
The features with the most significant impact on housing prices were:
Bathrooms: Coefficient = 1,097,117 (highest positive impact)
Air Conditioning: Coefficient = 785,550
Hot Water Heating: Coefficient = 687,881
Preferred Area: Coefficient = 629,901
Stories: Coefficient = 406,223

The Furnishing Status had a negative coefficient (-210,397), suggesting that unfurnished homes might decrease price, as opposed to furnished or semi-furnished options.

Correlation Analysis: The correlation matrix indicated strong relationships between several features and the target variable (price). For instance, the number of bathrooms and the presence of air conditioning had strong positive correlations with housing prices.

Model Performance: The R-squared value of 0.65 suggests the model captures a decent amount of the variability in prices, although there is room for improvement. This could be achieved through feature engineering, incorporating additional data, or trying more complex models.

Distribution of Prices: The histogram of housing prices indicated a right-skewed distribution, which is common in housing datasets, where a few houses have significantly higher prices than the majority.

Conclusion

The linear regression model successfully predicted housing prices based on several features, providing valuable insights into which characteristics of houses most influence their market value. Further enhancements could include experimenting with advanced regression techniques or integrating more predictive variables to improve accuracy.
