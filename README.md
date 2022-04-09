# MechaCar_Statistical_Analysis

## Overview

* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes

* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots

* Run t-tests to determine if the manufacturing lots are statistically different from the mean population

* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Linear Regression to Predict MPG

![Linear Regression to Predict MPG](https://user-images.githubusercontent.com/94339449/162590080-781df7ed-6f1e-4f46-9de0-588b3b587573.png)

In the image above we can see that:

* The vehicle_length and ground_clearance coeeficients do a provide a non-random amount of variance to the mpg values. We know this because a 95% level of confidence was predetermined, meaning the p-value should be compared to alpha = 0.05 level of significance to verify if statistically significant.

* With a p-Value of 5.35e-11, we can say that the slope is not zero. We know this because it is smaller then the assumed significance level of 0.05.

* With r-squared being .7149, that means the linear model does predict mpg of MechaCar prototypes effectively.

## Summary Statistics on Suspension Coils

