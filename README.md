# Phytoplankton-Modeling-in-the-James-River 
NASA SARP

This project aimed to establish a relationship between Landsat-8 multispectral imagery and in situ Chlorophyll-a (Chl-a) measurements along the James River. Data was obtained from Chesapeake Bay Program Database:[https://www.chesapeakebay.net/what/data] and NASA Landsat-8:[https://earthexplorer.usgs.gov/]. The code includes data preprocessing, visualization, and Regression algorithm development using various approaches including Principal Components Analysis (PCA). 

The following were the results from the projetct: 
Simple band ratio algorithms performed poorly with R-squared values below 0.1.
Regionally developed ocean color algorithm using PCA performed fairly well - 
63% of variability in Chl-a concentration explained by spectral information from Landsat-8 imagery; very small negative bias shows slight underestimation of Chl-a by model; MAE of 0.46 describes a small average error in model predictions.
