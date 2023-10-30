## Airbnb_Price_Prediction 

<img src = "https://github.com/Terry-Migwi/Airbnb_Price_Prediction/assets/65303250/fb0f4155-fc22-4af6-9c48-0228345ba48b" width = "350" height = "250"> 

### Project Overview 

This study aims to predict the prices of Airbnb listings in the City of Paris while harnessing the predictive capabilities of statistical and machine learning techniques. This study uses a `Multiple Linear Regression` model to explore any linear relationships between the variables. Then it introduces more complex nonlinear techniques such as `Support Vector Regression (SVR)` and `Multilayer Perceptron(MLP)` to learn the nonlinear patterns in the dataset. Further, more robust ensemble methods, namely `Random Forests`, `Gradient Boosting Machines`, and `eXtreme Gradient Boosting` are applied to learn complex patterns in the dataset for Airbnb price prediction. Moreover, the study delves into feature engineering and cross-validation to improve the model performance and also performs feature importance  using the best-performing models to unveil the importance of variables influencing Airbnb prices.

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
This notebook focuses on data pre-processing, exploratory data analysis, and price predicting using Linear Regression, Multi-layer Perceptron, Support Vector Regression, Gradient Boosting Machines, Random Forest, and XGBoost algorithms. Moreover, feature importance is investigated using Random Forest and XGBoost. 

### Results and Evaluation
The evaluation metrics used are Root Mean Squared Error (RMSE) and R-squared (R2). Given our research objective to leverage statistical and machine learning techniques to predict the prices of Airbnb listings in the City of Paris, the results demonstrate that machine learning techniques are more robust than statistical techniques in predicting the prices of Airbnb listings. The machine learning techniques produced a notably high performance, with the `XGBoost` having the highest performance with an `R-squared score of 0.65`, meaning that the model built explains 65% of the variability in house prices. However, the linear regression, a more statistical technique, had a relatively low R-squared score of 0.17 model performance. These results indicate that the data is not linearly separable and that machine learning techniques are more effective for predicting the price of Airbnb listings. Overall, the ensemble techniques result in the best model performance with the XGBoost, achieving an R-squared score of 0.65 and the Random Forest following closely with an R-squared score of 0.63. The performance of all the models is summarized in the table below. 

![image](https://github.com/Terry-Migwi/Airbnb_Price_Prediction/assets/65303250/201207e1-0841-41d6-a066-5ac10451cd52)

Feature importance was performed using Random Forest and XGBoost. They both had the variable `accommodates` as the most important feature. 

![image](https://github.com/Terry-Migwi/Airbnb_Price_Prediction/assets/65303250/adb16c63-d759-4e22-a51f-fda9e96eb434)


