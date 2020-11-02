# Heart Disease Prediction <h1> 
![](https://img.shields.io/badge/Dataset-Kaggle-blue) ![](https://img.shields.io/badge/Python-3.6-red) ![](https://img.shields.io/badge/Library-sklearn-orange)
  
### Project Overview
Classifying whether a person is suffering from Heart Disease or not.

### Resources Used

* Packages: **pandas, numpy, sklearn, matplotlib, seaborn.**
* Dataset by Ken Jee: https://www.kaggle.com/ronitf/heart-disease-uci

### Exploratory Data Analysis 
* Plotted heatmap to visualise the correlation between the features of the dataset
<p align="center">
<img src="https://github.com/ElenaElenoglou/Machine-Learning/blob/master/Heart%20Disease%20Prediction/readme_resources/heatmap.png" width="800" height="500" />
</p>
* Plotting histograms for the entire dataset
<p align="center">
<img src="https://github.com/ElenaElenoglou/Machine-Learning/blob/master/Heart%20Disease%20Prediction/readme_resources/histogram.png" width="800" height="500" />  
</p>
* Visualise the balance of the dataset
<p align="center">
<img src="https://github.com/ElenaElenoglou/Machine-Learning/blob/master/Heart%20Disease%20Prediction/readme_resources/dataset_balance.png" width="400" height="300" />  
</p>



### Feature Engineering

* Categorical variables into dummy variables
* Scale dataset with StandardScaler

### Model building & Evaluation
* **K Neighbors Classifier: 87%**
* Decision Tree Classifier: 79%
* Random Forest Classifier: 84%

![](readme_resources/K_Neighbors.png) 
![](readme_resources/Decision_Tree.png) 
![](readme_resources/Random_Forest.png)
