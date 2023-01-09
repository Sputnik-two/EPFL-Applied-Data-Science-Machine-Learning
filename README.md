# EPFL Extension School - Applied Data Science: Machine Learning
## Capstone Project: Predicting the duration of the insertion of real estate advertisements for rental apartments in Switzerland

According to a recent [study](https://www.tagesanzeiger.ch/so-wenig-wohnungen-wie-seit-10-jahren-nicht-mehr-nun-steigen-mieten-kraeftig-987026564282), there are currently very few vacant flats in Switzerland. The increasing shortage is reflected in the so-called insertion period. This value indicates how many days a residential property can be found on one of the real estate portals. According to the study, this period has been decreasing significantly for some time. However, the development is not the same across all municipalities and types for rental apartments. 

For this capstone project, I analysed the duration of insertion for rental apartments in Switzerland and detected patterns. My project goal was to find the model and features which best predicts the target variable, the duration of insertion of rental advertisements. The project contains data preparation, Exploratory Data Analysis (EDA) and different machine learning models.

For my project, data from three different sources are used: 
1. real estate advertisements for rental apartments in Switzerland from the years 2015 to 2020
2. statistics on the housing market 
3. spatial categories for the municipalities

In the Machine Learning part, three models are tested and tuned:
* Lasso Regression
* kNN Regression
* RandomForest Regression

The folder contains the following notebooks:
* 01_Preparation_Ads
* 02_Preparation_Stats
* 03_Exploratory Data Analysis
* 04_ML_Lasso
* 05_ML_knn
* 06_ML_Random Forest
* 07_ML_Results

__Example an advertisement - Source: ImmoDataCockpit__

<img width="734" alt="image" src="https://user-images.githubusercontent.com/95368630/207430717-3aaa4a5e-9dc1-43b4-bea8-3d629a259dfc.png">
