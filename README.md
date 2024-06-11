Car Price Prediction Project :

Description: 
This project focuses on predicting car prices using various machine learning models. The dataset includes features such as model, year, mileage, fuel type, and transmission type. The goal is to build a model that accurately estimates the price of a car based on these features.

Libraries and Tools Used:
Python
NumPy
Pandas
Matplotlib
Scikit-learn
CatBoost
Pickle

Data Preprocessing:
Feature and Target Separation: The dataset is split into features (X) and target variable (y).
Label Encoding: Categorical features like 'model' and 'fuelType' are label encoded.
One Hot Encoding: The 'transmission' feature is one hot encoded.
Feature Scaling: The features are standardized using StandardScaler.

Modeling: 
Several machine learning models were trained and evaluated.

Model Evaluation: 
The models were evaluated based on R2 Score and Mean Absolute Error (MAE). The tuned Random Forest model and CatBoost Regressor showed the best performance.

Conclusion:
The project successfully developed a machine learning model to predict car prices with high accuracy. The tuned Random Forest Regressor and CatBoost Regressor provided the best results. The final model was saved using Pickle for future use.

