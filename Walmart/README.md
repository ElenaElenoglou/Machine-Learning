<img src="https://www.bestdesigns.co/uploads/inspiration_images/4350/990__1511457498_404_walmart.png" alt="WALMART LOGO">

# Walmart : predict weekly sales

![](https://img.shields.io/badge/Dataset-Jedha-lightgrey) ![](https://img.shields.io/badge/Python-3.6-red) ![](https://img.shields.io/badge/libraries-pandas-green) ![](https://img.shields.io/badge/libraries-plotly-pink) ![](https://img.shields.io/badge/libraries-searborn-blue) ![](https://img.shields.io/badge/libraries-sklearn-blueviolet)



## Company's Description 📇

Walmart Inc. is an American multinational retail corporation that operates a chain of hypermarkets, discount department stores, and grocery stores from the United States, headquartered in Bentonville, Arkansas. The company was founded by Sam Walton in 1962.



## Project 🚧
Walmart's marketing service has asked you to build a machine learning model able to estimate the weekly sales in their stores, with the best precision possible on the predictions made. Such a model would help them understand better how the sales are influenced by economic indicators, and might be used to plan future marketing campaigns.



## Scope of this project 🖼️
For this project, we'll work with a dataset that contains information about weekly sales achieved by different Walmart stores, and other variables such as the unemployment rate or the fuel price, that might be useful for predicting the amount of sales. 🤓



## Resources Used 📖

- Packages: **pandas, numpy, sklearn, matplotlib, seaborn, plotly.**
- Dataset by Jedha.



## Exploratory Data Analysis & Data Cleaning

- **Plotted plotted variety of plots ** for numerical and categorical features respectively.



<img src="C:\Users\elena\Documents\Fullstack\FullStack_Projects\Module_2_Supervised_ML\Walmart\Images\time_plots.png" alt="time_plots" style="zoom:67%;" />





<img src="C:\Users\elena\Documents\Fullstack\FullStack_Projects\Module_2_Supervised_ML\Walmart\Images\Correlation_matrix.png" alt="Correlation_matrix" style="zoom: 80%;" />



- **Removed unwanted columns**.

  

## Feature Engineering <img src="https://icon-library.com/images/free-gear-icon/free-gear-icon-6.jpg" alt="Free Gear Icon #393789 - Free Icons Library" style="zoom:5%;" />

- **Feature Scaling:** numerical and categorical features.
- **Imputing missing values:** KNN Imputer.



## Model building & Evaluation  <img src="https://cdn4.iconfinder.com/data/icons/business-data-and-growth-color/64/growth-blocks-512.png" alt="About us, blocks, build, business, finance, growth, building blocks icon -  Download on Iconfinder" style="zoom:10%;" />

Metric:  Root Squared Error (RSE)

- Linear Regression: 0.98.
- Ridge Regression: 0.93.
- Lasso Regression : 0.98.
- **Hyperparameter Tuning:**  Ridge: 0.98,  Lasso: 0.98.

