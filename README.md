# Lab10: Airbnb Price Prediction in Columbus, Ohio

Author: Phuong Le  
Date: November 8, 2023  
Data Attribution: Dr. Alexandre Scarcioffolo

## Overview

This project explores and analyzes Airbnb data from Columbus, Ohio, collected on September 21, 2022. The goal is to identify key factors influencing rental prices and to develop a linear regression model that can predict prices based on those factors.

## Table of Contents

- [Introduction](#introduction)
- [Data Exploration](#data-exploration)
- [Statistical Analysis and Interpretation](#statistical-analysis-and-interpretation)
- [Model Validation](#model-validation)
- [Conclusion](#conclusion)

## Introduction

The dataset comprises information on Airbnb listings in Columbus, Ohio. The analysis aims to identify key factors that influence prices and develop a predictive model. It's important to note that the data may not fully represent the long-term market due to the potential effects of the COVID-19 pandemic on the accommodation industry.

## Data Exploration

The initial data exploration involved cleaning and transforming the data, particularly focusing on converting variables like price and the number of bathrooms into numerical values for analysis.

### Key Visualizations

- **Price Distribution**: The price distribution is skewed to the left, indicating a concentration of listings around the $125 mark.
- **Effect of Number of Beds on Price**: A positive relationship between the number of beds and price was observed.

## Statistical Analysis and Interpretation

A linear regression model was developed to predict prices based on the number of beds, bathrooms, and review accuracy scores. The model demonstrated that all three predictors have a statistically significant positive relationship with price.

### Model Summary

- **Intercept**: 4.00579
- **Log of Beds Coefficient**: 0.55883
- **Review Scores Accuracy Coefficient**: 0.07450
- **Log of Bathrooms Coefficient**: 0.19929
- **R-squared**: 0.4258

The model explains approximately 42.58% of the variation in price, indicating a moderate fit.

## Model Validation

The model's assumptions were validated through diagnostic plots, which confirmed linearity, normality of residuals, homoskedasticity, and independence of residuals. The histogram of residuals also indicated a good fit, with minimal outliers.

## Conclusion

The analysis identifies that the number of beds, bathrooms, and review accuracy scores are significant predictors of Airbnb rental prices in Columbus. However, the model's predictive power is limited by the exclusion of other potential factors like location and property features.

## Acknowledgments

- **Data Attribution**: The dataset was provided by Dr. Alexandre Scarcioffolo, whose contributions were invaluable to this project.

## References

- [Airbnb's Impact on Neighborhood Crime](https://www.wgbh.org/news/local-news/2021/07/22/airbnb-impacts-neighborhood-crime-but-not-in-the-way-you-think)
- [Airbnb and Housing Shortages](https://slate.com/business/2021/10/airbnb-housing-shortage-luxury-vacation-rental-galveston-texas.html)
