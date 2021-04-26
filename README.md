# Indonesia Economic Crisis Prediction Using Random Forest
This is an implementation of machine learning for predicting Indonesia Economy Crisis using Random Forest Method

## Overview
Economic crisis is a severe and sudden upset in any part of the economy. It could be a stock market crash, a spike in inflation or unemployment, or a series of bank failures. They have severe effects even though they don't always lead to a recession. To prevent this, the government must take actions based on several economic variables. The variables provided for this model is :
* Ekspor
* Cadangan Devisa
* IHSG
* Selisih Pinjaman dan Simpanan
* Suku Bunga Simpanan Riil
* Selisih BI Rate Riil dan FED Rate Riil
* Simpanan Bank
* Nilai Tukar Riil
* Nilai Tukar Perdagangan
* M1
* M2/Cadangan Devisa
* M2M
* Krisis (Output/y variable)

After you understands the data and the variables, there is some steps you must take before proceeding to modelling :
* Data Cleaning and Preprocessing
* Data Partition
* SMOTE (Synthetic Minority Oversampling Technique)

In the end, this model generate result :
* 98.45% on Data Testing Accuracy
* 94.44% on Random Forest Accuracy
* etc. (you can look it up in the code file)

The original dataset is from :<br>
https://www.kaggle.com/c/shift-academy-data-science-bootcamp-10/data
