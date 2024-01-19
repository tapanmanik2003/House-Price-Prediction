# Project Title: House Price PredicƟon
## Introduction
 - The goal of this project is to predict house prices based on various features using machine learning models. 
## Dataset 
 - The dataset, 'house price.csv,' was used for this project. 
 - IniƟal exploraƟon
 - Dataset shape 
 - First 5 rows 
 - Dataset info 
##vHandling Missing Values 
 - Columns with more than 500 missing values were dropped. 
 - Specific columns were imputed with mean or 'NA' based on context. 
## Feature Engineering 
 - Created scaƩer plots to idenƟfy outliers in 'GrLivArea' and 'LotArea'.
 - Removed outliers beyond certain thresholds. 
## Encoding 
 - Label encoded categorical columns using sklearn's LabelEncoder. 
 - Applied one-hot encoding for beƩer model compaƟbility.
## Exploratory Data Analysis (EDA) 
 - Analyzed correlaƟon between features and target variable ('SalePrice').
 - Visualized relaƟonships through scaƩer plots, pie charts, and bar plots for key features.
## Model Training and EvaluaƟon
 - Train-Test Split 
 - Split the dataset into training and tesƟng sets (80-20 split). 
## Model SelecƟon
 - Trained and evaluated the following models: 
 - RandomForestRegressor 
 - LinearRegression 
 - DecisionTreeRegressor 
 - XGBRegressor 
## Model EvaluaƟon Metrics
 - Used metrics such as Model Score, Mean Absolute Error (MAE), and Mean Squared Error (MSE) to evaluate model performance. 
## Results
 - RandomForestRegressor achieved the highest model score and lowest MAE and MSE among the models.
