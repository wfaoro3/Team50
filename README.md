Team50 Repository Documentation

Note: All files can also be found on github here: https://github.com/wfaoro3/Team50

Overview
This repository contains various R and Python code files for analyzing flight data, focusing on delays, cancellations, and city-specific trends. The primary datasets used span the years 2018-2023. Our final dashboard can be found by opening team050dashboard.html.

Setup Instructions
For R Files:
Required Packages: foreign, dplyr, missForest, leaps, xtable, rpart, rpart.plot, RColorBrewer, ggplot2, rattle, maptree, glmnet, logistf.

Installation Command:
install.packages(c("foreign", "dplyr", "missForest", "leaps", "xtable", "rpart", "rpart.plot", "RColorBrewer", "ggplot2", "rattle", "maptree", "glmnet", "logistf"))

For Python Notebooks:
Required Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn.
Installation Command:
!pip install pandas numpy matplotlib seaborn scikit-learn

File-Specific Setup
Group 50_Delay 15 Min by Type_CODE.Rmd and Team 50_City_vs_Cancellation_CODE.Rmd use the same set of R packages.
Logistic_Regression.Rmd requires a subset of these packages.
Linear_and_Logistic_Regression_EDA.ipynb and data_cleanup.ipynb require Python libraries.

Files and Their Purposes
Data Source (used for all files from TransBTS): flights_2018_2023_top_airports.csv
TransBTS: https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGK&QO_fu146_anzr=b0-gvzr

Filename: Team 50_City_vs_Cancellation_CODE.Rmd
Purpose: Analyzes flight cancellation data for specific cities using decision tree models.
Execution: File can be run as is, can be updated to use new months, years data on flights from TransBTS.Decision trees are not intended for prediction, so they are not to be updated. Rather, they should be looked back on as a point in time.

Filename: Group 50_Delay 15 Min by Type_CODE.Rmd
Purpose: Analyzes flight delays over 15 minutes, categorized by type using decision tree models.
Execution: File can be run as is, can be updated to use new months, years data on flights from TransBTS. Decision trees are not intended for prediction, so they are not to be updated. Rather, they should be looked back on as a point in time.

Filename: Linear_and_Logistic_Regression_EDA.ipynb
Purpose: Performs data preprocessing, logistic regression modeling, and exploratory data analysis (EDA) to predict flight cancellations.
Execution: File can be run as is, can be updated to use new months, years data on flights from TransBTS

Filename: Logistic_Regression.Rmd
Purpose: Involves data analysis and logistic regression modeling, generating a CSV of the model's coefficients.
Execution: File can be run as is, can be updated to use new months, years data on flights from TransBTS

Filename: data_cleanup.ipynb
Purpose: Focuses on cleaning and preparing the flights dataset for further analysis.
Execution: File can be run as is, can be updated to use new months, years data on flights from TransBTS

Filename: FindingBetterWaystoFly.twbx
Purpose: Tableau workbook contains all visualizations
Execution: Open and connect attributed data sources, which can be found in the tableau_datasources folder.

Filename: dva_team50.html
Purpose: Contains all visualizations and analysis combined. Serves as our tool for the end user.
Execution: Simply open the HTML file and toggles can be used to play around on it. 

DASHBOARD LINK: Dashboard can also be found on Tableau Public at https://public.tableau.com/app/profile/aparna.kakarlapudi2429/viz/FindingBetterWaysToFly/FindingBetterWaystoFly#1
