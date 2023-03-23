# Zillow Data Analysis

In this project, my team explored what kind of listing description makes a home sell faster and what things realtors should emphasize when trying to present a house. 

## Description of R Files
1. Data Cleaning Script - This file cleans and preps the “census” and “zillow” datasets for analysis. For zillow, we fixed the column headers, converted data types to numeric if needed, imputed NA values, took out data with more than 50% values being NA, and narrowed zip codes to only include neighborhoods with middle-class incomes on average. For census, we also fixed and renamed column headers, converted data types, filtered out non-LA zip codes, and narrowed zip codes to only include neighborhoods with middle-class incomes on average.
2. wordclouds.Rmd - This file includes the code for some wordclouds we made.
3. zillow_data_analysis.Rmd - This file includes the NLP analysis I independently did on tf-idf, rake, and cooc.

I have also included the relevant CSV files should you wish to run my analysis from zillow_data_analysis.Rmd

The final_presentation.pdf file features the slide deck we created to present our findings. You may find the visualizations I have created on tf-idf, rake and cooc there.
 