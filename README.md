# Starbucks Capstone Data Science Project
This is a data science capstone project from Udacity. 

## 1. Project Motivation
The data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

The task is to combine transaction, demographic and offer data to determine how to increase offer engagement & offer completion rate.

## 2. Files
Below files/folders are contained in this repo.
* `data`: Folder contains all data files used for the project.
  1. `portfolio.json`: containing offer ids and meta data about each offer (duration, type, etc.)
  2. `profile.json`: demographic data for each customer
  3. `transcript.json`: records for transactions, offers received, offers viewed, and offers completed


* `Capstonoe_YI.ipynb` Jupyter Notebook conducting the project analysis

## 3. Required Packages
`Numpy`   
`Pandas`   
`math`  
`json`  
`datetime`    
`seaborn`    
`matplotlib`     
`sqlite3`    
`sklearn`     
`warning`     

## 4. Analysis Result
Based on analysis, the following business solution can be provided to solve the problem:
  1. Start increasing proportion of offers sent through social media (increase offer view rate)
  2. Send more discount offers. Target on offers `fafdcd668e3743c1bb461111dcafc2a4` and `2298d6c36e964ae4a3e7e9706d1fb8c2`.
  3. Tartet customers with high income, high total dollar spending, 3~4 years of tenure and age above 55.

## 5. Acknowledgements
Data sourced from Udacity.
