# **Restaurant Satisfaction EDA & Prediction**


**Project Overview**

This notebook analyzes a restaurant satisfaction dataset to explore the factors influencing customer happiness and to build a predictive model for satisfaction levels. The dataset includes details such as group size, dining occasion, and visit time, which were examined to uncover patterns in customer sentiment. I began with exploratory data analysis to identify trends, such as how different occasions or group sizes affect satisfaction scores, and moved on to creating a model to predict whether a customer’s satisfaction would be high or not.

**Methods & Results**

The analysis started with data cleaning and visualization, highlighting which features were most associated with higher satisfaction. Relationships between dining occasion, group size, and time of day were visualized to identify key patterns. A logistic regression model was then built, using a balanced class weight to address the dataset’s imbalance between high and low satisfaction ratings. The model’s performance was evaluated using a classification report and confusion matrix, showing moderate predictive ability, with room for improvement if additional variables were available.

**Key Outputs**

- Cleaned and processed restaurant satisfaction dataset
- Visualizations showing satisfaction by group size, dining occasion, and visit time
- Logistic regression model for predicting satisfaction
- Classification report and confusion matrix for model evaluation
- Insights into which customer segments are most likely to report high satisfaction

**Conclusion**

The results suggest that customer satisfaction is shaped by multiple factors, including group size and dining occasion, but the dataset likely lacks some influential variables that could improve prediction accuracy. This analysis provides a foundation for restaurants to better understand and target their most satisfied customers, and the model can be refined further with additional behavioral or demographic data.
