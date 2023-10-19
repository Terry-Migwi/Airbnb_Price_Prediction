## Airbnb_Price_Prediction 

### Project Overview
The objective of this study is to perform price prediction for Airbnb listings in the city of Paris using Machine Learning techniques with the following aims:  

1.   Explore linear relationships between variables for price prediction using linear models.
2.   Find complex non-linear patterns between the variables using non-linear models and ensemble techniques.

### Installation and Setup
Clone the repository: git clone https://github.com/Terry-Migwi/Airbnb_Price_Prediction.git

### Resources Used
* Editor: Google Colaboratory
* Python Version: Python 3

### Packages Used
* General purpose packages: itertools
* Data manipulation packages: pandas, numpy, scipy
* Data Visualization: seaborn, matplotlb
* Machine Learning: sklearn, TensorFlow

### Data
The dataset was obtained from http://insideairbnb.com/get-the-data/. It contained 61,706 listings for June 2023 with 20 different neighborhoods in Paris. 

### Code Structure
This project has one notebook ```Airbnb_Price_Prediction.ipynb ``` 
This notebook focuses on data pre-processing, exploratory data analysis, and price predicting using Logistic Regression, Multi-layer Perceptron, Support Vector Regression, Gradient Boosting Machines, Random Forest, and XGBoost algorithms. Moreover, feature importance is investigated using Random Forest and XGBoost. 

### Results and Evaluation
Model performance was compared using Root Mean Squared Error(RMSE) and R-squared scores. The linear models had the worst model performance while ensemble techniques had the best performing models. The model performance is summarized in the table below. 

![image](https://github.com/Terry-Migwi/Airbnb_Price_Prediction/assets/65303250/201207e1-0841-41d6-a066-5ac10451cd52)

Feature importance was performed using Random Forest and XGBoost. They both had the variable "accommodates" as the most important feature. 

![image](https://github.com/Terry-Migwi/Airbnb_Price_Prediction/assets/65303250/adb16c63-d759-4e22-a51f-fda9e96eb434)


