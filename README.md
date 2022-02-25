# Cryptocurrencies

## Overview of Project

### Purpose

The purpose of this project is to show what cryptocurrencies are on the trading market and how they could be grouped to create a classification system. The data is not ideal, so it will be processed to fit the machine learning models. Since there is no known output, unsupervised machine learning will be used, and to group the cryptocurrencies, we decided on a clustering algorithm using K-means.

First, the data was preprocessed for Principal Component Analysis (PCA), and then all the data dimensions were reduced to three principal components. Then we clustered the PCA cryptocurrencies data using K-means. Finally we visualized the results with Plotly Express 3D scatter plot and 2D hvPlot.
