# uc_berk_coupon
Based on the analysis of the Jupyter notebook "coupon_analysis_bhargav_gundabolu.ipynb", here's a structured README documentation:

---

# Coupon Analysis Project

## Overview

This project explores the factors influencing whether a driver would accept a coupon delivered to their cell phone while driving. It uses data from the UCI Machine Learning repository, collected via a survey on Amazon Mechanical Turk, to analyze different driving scenarios and the likelihood of coupon acceptance. The study focuses on various factors such as destination, time, weather, passenger, and more.

## Data Description

The dataset includes the following attributes:

1. **User Attributes**: 
   - Gender
   - Age
   - Marital Status
   - etc.

2. **Geographical Attributes**: 
   - Location of user, coupon, and destination
   - Weather conditions
   - Temperature
   - Time
   - Passenger type (alone, partner, kids, friends)

3. **Coupon Attributes**: 
   - Type of coupon (restaurants, coffee houses, bars, etc.)
   - Time before expiration

Note: The values mentioned are average values.

## Problems and Tasks

1. **Data Reading**: Import and process the `coupons.csv` file.
2. **Data Cleaning**: Address missing values in various columns, such as 'Bar', 'CoffeeHouse', 'CarryAway', 'RestaurantLessThan20', and 'Restaurant20To50'.

## Independent Investigations

Conduct exploratory data analysis to understand the characteristics of passengers who accept different types of coupons. For example, analyze the acceptance of bar coupons and extend the investigation to other coupon categories.

## Key Findings

1. **Acceptance Rate by Passenger Type**: Analyze how different passenger configurations (alone, with friends, etc.) influence the acceptance rate of specific coupon types like Coffee House coupons.

2. **Acceptance Rate by Age Group**: Investigate the acceptance rates across different age groups to identify trends or preferences.

3. **Acceptance Rate by Income Level**: Examine how income levels impact the likelihood of accepting coupons, particularly for Coffee House coupons.

---

This documentation provides a comprehensive overview of the project, including the context, data description, key problems, and areas of investigation.
