## **Car Price Prediction with Multiple Linear Regression**
### **Project Overview**
This project involves building a multiple linear regression model to predict car prices for Geely Auto, a Chinese automobile company looking to enter the US market. The goal is to analyze and understand the factors influencing car prices in the American market.

**Objectives**
- Identify significant variables affecting car prices.
- Assess the accuracy and explanatory power of these variables in predicting car prices.
- Provide actionable insights to adjust car designs and business strategies for the US market.

### **Data Preparation**
- **CarName Variable:** The dataset includes a CarName variable combining the car company name and model. For model building, only the car company name is used as an independent variable.
- **Data Cleaning:** Preprocess the dataset by handling missing values and encoding categorical variables as needed.
   
### **Model Building**
- Approach: Multiple linear regression is employed to model car prices based on the independent variables.      
- Evaluation: The model's performance is evaluated using the R-squared score, calculated with:

from sklearn.metrics import r2_score       
r2_score(y_test, y_pred)

### **Deliverables**
**Python Notebook:** Contains data preparation, model building, predictions, and evaluation.          
**Subjective Questions Ms Word:** Answers to questions related to linear regression.
