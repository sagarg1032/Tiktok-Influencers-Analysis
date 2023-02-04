# Tiktok Influencer Analysis

This repository contains the code for analyzing data related to Tiktok Influencer. The data includes the number of subscribers, average views, average likes, average comments, and average shares. The analysis is done using pandas, numpy, re, seaborn, and matplotlib libraries. The purpose of the analysis is to explore the data, clean it, and find the correlation between different features.

## Requirements
* Pandas
* Pandas Profiling
* Seaborn
* Matplotlib

## Usage
* Clone the repository
* Run the Jupyter Notebook
* Download the dataset from my GitHub repository
* Replace the path of the csv file in line df = pd.read_csv(r"C:\Users\saggupta2\Downloads\social media influencers - Tiktok sep 2022.csv") with the path to your csv file
* Run all cells in the Jupyter Notebook
* Go through Tiktok_report.html to get a general understanding of dataset 



## File description
* '**Tiktok Influencer Analysis.ipynb**' :  Jupyter Notebook containing the code for the analysis.

## Analysis Description

* Import necessary libraries
* Read the csv file into a pandas dataframe
* Check the columns and number of rows and columns in the dataframe
* Check for missing values in the dataframe
* Drop duplicate rows and unnecessary columns
* Convert the subscribers, views avg., likes avg., comments avg., and shares avg. columns into float values
* Check for missing values in the dataframe again
* Calculate the correlation between different features using the Pearson method
* Plot heatmap to visualize the correlation
* Plot scatter plots to show the correlation between likes avg. and views avg. and between subscribers and likes avg. and between subscribers and views avg.

## Result

The result of the analysis shows a high correlation between likes avg. and views avg., subscribers and likes avg., and subscribers and views avg.

## Source
https://www.kaggle.com/datasets/ramjasmaurya/top-1000-social-media-channels
