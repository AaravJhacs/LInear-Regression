# **Project Description: Advertising Sales Prediction Using Linear Regression**

**Overview**

This project aims to predict sales generated from advertising spending using linear regression models. The dataset utilized for this project contains information on advertising spending across three media channels: TV, radio, and newspaper, along with the corresponding sales figures. The project explores both simple and multiple linear regression techniques to build predictive models.

**Objectives**

**Data Exploration and Visualization:**

Load and visualize the dataset to understand the relationship between advertising spending and sales.
Use scatter plots and heatmaps to identify correlations between different features and the target variable (sales).
Simple Linear Regression:

Implement a simple linear regression model using TV advertising spending as the predictor.
Evaluate the model's performance on training and test datasets.
Interpret the model coefficients to understand the impact of TV advertising on sales.
Multiple Linear Regression:

Extend the model to include radio and newspaper advertising spending as additional predictors.
Evaluate the multiple linear regression model's performance on training and test datasets.
Use the model to make predictions on new data.
Data Exploration and Visualization

**Data Loading:** The dataset is loaded from a CSV file using pandas.<br/>
**Visualization:** Scatter plots are created using matplotlib and seaborn to visualize the relationship between each advertising channel and sales.<br/>
**Correlation Analysis:** A correlation matrix is computed and visualized using a heatmap to identify the strength of relationships between features.<br/>

**Simple Linear Regression**

**Feature Selection:** TV advertising spending is selected as the predictor variable.<br/>
**Model Training:** The dataset is split into training and test sets. A linear regression model is trained using the training set.<br/>
**Model Evaluation:** The model's performance is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared on both training and test data.<br/>
**Prediction:** The model is used to predict sales for a new market with a specific TV advertising spend.

**Multiple Linear Regression**

**Feature Selection:** TV, radio, and newspaper advertising spending are selected as predictor variables.<br/>
**Model Training:** The dataset is again split into training and test sets. A multiple linear regression model is trained using the training set.<br/>
**Model Evaluation:** Similar to the simple linear regression, the model's performance is evaluated using MAE, MSE, RMSE, and R-squared on both training and test data.<br/>
**Prediction:** The model is used to predict sales for new data containing advertising spends across TV, radio, and newspaper.<br/>

**Results**

The simple linear regression model shows a significant positive correlation between TV advertising spend and sales.<br/>
The multiple linear regression model provides a more comprehensive understanding by including additional predictors (radio and newspaper), resulting in improved prediction accuracy.<br/>

**Conclusion**

This project demonstrates the application of linear regression techniques to predict sales based on advertising spending. The insights gained from the analysis can help businesses make informed decisions on optimizing their advertising budgets across different media channels to maximize sales.

**Future Work**

Explore more advanced regression techniques, such as polynomial regression or regularized regression (Ridge, Lasso).<br/>
Investigate the impact of interaction terms between different advertising channels.<br/>
Incorporate additional features (e.g., seasonal factors, market conditions) to improve the model's predictive power.<br/>

**Dependencies**

Python 3.x<br/>
pandas<br/>
numpy<br/>
matplotlib<br/>
seaborn<br/>
scikit-learn<br/>
How to Run<br/>

Ensure all dependencies are installed.<br/>
Load the dataset (Advertising.csv) and run the code cells sequentially in a Jupyter Notebook or a Python script.<br/>
Use the provided code snippets to train the models, evaluate their performance, and make predictions on new data.<br/>
