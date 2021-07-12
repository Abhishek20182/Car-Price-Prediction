<p align="center">
  <img src='https://cdn.geekwire.com/wp-content/uploads/2020/01/20200108_CES_603-1260x840.jpg' alt="car" width = 300px>
</p>


<h2 align="center">Car Price Prediction - Machine Learning</h2>

![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue)
![Python](https://img.shields.io/badge/Python-3.7-green)
![Library](https://img.shields.io/badge/Library-Sklearn-orange)


## Table of Contents
- [Installation](#installation)
- [Results](#results)
- [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
You need to be able to work in a Jupyter Notebook on your computer. The following packages (libraries) need to be installed. You can install these packages via conda or pip.

- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scikit learn

## Results <a name="results"></a>
- The Distribution of Price is main problem beacuse it was skewed right, and gives large error in train and test. So, to solve this problem I have used Log Transformation. 
<p align="center">
  <img src='https://github.com/Abhishek20182/Car-Price-Prediction/blob/main/readme-resources/price.png' alt="price_distribution">
</p>

<p align="center">
  <img src='https://github.com/Abhishek20182/Car-Price-Prediction/blob/main/readme-resources/price_log.png' alt="price_log_distribution">
</p>

- **Correlation Matrix**: This gives an brief idea about connection between each other (Here target variable is msrp).
<p align="center">
  <img src='https://github.com/Abhishek20182/Car-Price-Prediction/blob/main/readme-resources/data_corr.png' alt="Data_Correlation">
</p>

- **Final Results on Train and Test Data**
<p align="center">
  <b>Prediction Vs Actual Distribution on Train Data</b> <br>
  <img src='https://github.com/Abhishek20182/Car-Price-Prediction/blob/main/readme-resources/result_train.png' alt="train_dist">
</p>

<p align="center">
  <b>Prediction Vs Actual Distribution on Test Data</b> <br>
  <img src='https://github.com/Abhishek20182/Car-Price-Prediction/blob/main/readme-resources/result_test.png' alt="test_dist">
</p>

- **Meteric used:**
     - **Root Mean Square Error (RMSE): 0.0708 on Train DataSet and 0.1078 on Test DataSet.**
 
## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Must give credit to Kaggle for the data. You can find the Licensing for the data and other descriptive information at the [Here](https://www.kaggle.com/CooperUnion/cardataset).
