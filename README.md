# House Price Prediction - 2022 Python Data Science Project

## Overview
This project focuses on predicting house prices in the state of New York by utilizing data obtained through web scraping of the "Realtor" website. The raw data was carefully cleaned and visualized to provide valuable insights. The prediction models were built using linear regression, Lasso regression, and Bayesian models. The project is developed using popular Python libraries such as Pandas, NumPy, Scikit-learn, and Matplotlib.

## Table of Contents
Installation
Usage
Data Collection
Data Cleaning
Exploratory Data Analysis
Machine Learning Models
Results
Contributing
License
Installation
To get started with the project, follow these steps:

### Clone the repository:
```git clone https://github.com/veronika8597/House_Price_Prediction.git```

### Navigate to the project directory:
```cd House_Price_Prediction```

## Usage
### Data Collection - ```Realtor_NewYork_Scraping.ipynb```
The dataset was created by crawling the "Realtor" website, focusing on properties in the state of New York. 
Afterwards the raw data was saved in the RealEstateNeyYork.csv file.

### Data Cleaning - ```Cleaning_Data.ipynb```
The raw data obtained was meticulously cleaned to ensure accurate and reliable results in subsequent analyses. 
Then saved into the RealEstateNeyYork_Clean.csv file.

### Exploratory Data Analysis - ```EDA.NewYork.ipynb```
Visualizations and statistical analyses were performed to gain insights into the dataset. 

### Machine Learning Models - ```Realtor_ML.ipynb```
Implemented machine learning models include:

•  Linear Regression

•  Lasso Regression

•  Bayesian Models

These models were trained on the cleaned data to predict house prices based on the various features that were chosen for all the listings. 

## Results
The Lasso model demonstrated superior predictive accuracy among our models. Key findings include:
*  Identification of parameters with the most significant influence on the asset's selling price.

*  Post-deployment analysis of our predictive models highlighted the crucial role of "before and after" feature engineering.

*  A comparison of True Prices (average: $663,308.42) and Predicted Prices (average: $662,135.04) revealed a close alignment.

## Contributing
Feel free to contribute by opening issues, proposing new features, or providing suggestions. We welcome your input!

Project Link: ```House Price Prediction - GitHub```

