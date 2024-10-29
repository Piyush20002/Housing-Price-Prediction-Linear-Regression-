# Housing-Price-Prediction-Linear-Regression-
Housing Price Prediction ( Linear Regression )

Key Concepts and Challenges:
1. Data Collection: Obtain a dataset with numerical features and a target variable for prediction. 
2. Data Exploration and Cleaning: Explore the dataset to understand its structure, handle missing values, and ensure data quality. 
3. Feature Selection: Identify relevant features that may contribute to the predictive model. 
4.Model Training: Implement linear regression using a machine learning library (e.g., ScikitLearn). 
5. Model Evaluation: Evaluate the model's performance on a separate test dataset using metrics such as Mean Squared Error or R-squared. 
6. Visualization: Create visualizations to illustrate the relationship between the predicted and actual values. 

Summary of Steps
Data Loading and Exploration:

Loaded a dataset from a CSV file and displayed the first and last few records.
Checked the dataset for shape, missing values, and data types.
Data Cleaning:

Confirmed there are no missing values.
Identified outliers using the Interquartile Range (IQR) method.
Visualized the distributions and outliers using box plots and a histogram.
Data Visualization:

Plotted correlation matrices to analyze relationships between numerical features and the target variable (price).
Used pair plots to visualize interactions between variables.
Data Preprocessing:

Converted categorical variables to numerical format using label encoding.
Prepared the features (X) and target (y) for model training.
Model Training:

Split the dataset into training and testing sets (80-20 split).
Trained a linear regression model on the training set.
Model Evaluation:

Calculated performance metrics.
Visualized the relationship between actual and predicted prices using scatter plots and regression plots.
