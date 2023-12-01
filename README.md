# Team50
Group 50 - Delay >15 Min by Type CODE 
Overview 
This repository contains R code for analyzing flight delays greater than 15 minutes, categorized by delay types. The analysis focuses on the years 2018-2023 and uses data from the "flights_2018_2023_top_airports.csv" file. 

Setup 
Before running the R code, ensure you have the necessary R packages installed. You can install them using the following commands: 

install.packages(c("foreign", "dplyr", "missForest", "leaps", "xtable", 
                   "rpart", "rpart.plot", "RColorBrewer", "ggplot2", 
                   "rattle", "maptree"))


Linear_and_Logistic_Regression_EDA.ipynb 
Overview: 
The provided Python code seems to be a combination of data preprocessing, logistic regression modeling, and exploratory data analysis (EDA) tasks. The primary goal appears to be predicting flight cancellations based on various features. 

Setup: 
    Libraries Used: 
    pandas: Data manipulation and analysis. 
    matplotlib and seaborn: Data visualization. 
    scikit-learn: Machine learning models and tools. 
!pip install pandas matplotlib seaborn scikit-learn
 
 
Logistic_Regression.Rmd 
Overview: 
The provided R Markdown (Rmd) Notebook involves data analysis, logistic regression modeling, and the generation of a CSV file containing the coefficients of the logistic regression model. 

Setup: 
    install.packages(c("ggplot2", "glmnet", "logistf", "rpart", "rpart.plot"))


Team 50_City_vs_Cancellation_CODE.Rmd 
Overview: 
The provided R Markdown (Rmd) document, titled "City vs Cancellation CODE," focuses on analyzing flight cancellation data for specific cities (Chicago, IL; New York, NY; Newark, NJ). The analysis involves decision tree models to predict flight cancellations for each city. 

Setup: 
    Libraries Used: 
    install.packages(c("foreign", "dplyr", "missForest", "leaps", "xtable", 
                   "rpart", "rpart.plot", "RColorBrewer", "ggplot2", 
                   "rattle", "maptree"))


data_cleanup.ipynb 
Overview: 
The notebook focuses on cleaning and preparing our flights dataset for further analysis. 

Setup: 

import pandas as pd \n
import numpy as np
!pip install pandas numpy
