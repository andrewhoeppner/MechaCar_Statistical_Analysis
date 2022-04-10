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

![lot_summary](https://user-images.githubusercontent.com/94339449/162595316-8da6a661-6b49-4a01-a5e8-97d4c8601dae.png)
![total_summary](https://user-images.githubusercontent.com/94339449/162595326-2a22f7c4-9767-4b21-95c7-ec74d666f09e.png)

The variance of the suspension coils must not exceed 100 pounds per square inch. In the total_summary this is true with a variance of 62.3. This is also true for lots 1 and 2, however lot 3 has a variance of 170.29 which is well above the allowed variance of 100. Therefore lot 3 does not meet the necessary suspension coil requiremenets.

## T-Tests on Suspension Coils

![summary_ttest](https://user-images.githubusercontent.com/94339449/162595758-8f358af9-af0b-47ee-9dda-74982cca0720.png)

The image above shows a T-test of all the lots. With the p-value being 0.06028 it is still greater then 0.05, which means the total manufacturing lot is not statistically significant from the normal distribution and normality can be assumed.

![3_lots_ttest](https://user-images.githubusercontent.com/94339449/162596011-77a7097b-0127-40e6-ac50-52dadeec4ee8.png)

The above image shows a T-test for lots 1-3.

### Lot 1
Lot 1 has a p-value of 1 which is greater then 0.05, therefore lot 1 is not statistically significant from the normal distribution and normality can be assumed.

### Lot 2
Lot 2 has a p-value of 0.6072 which is greater then 0.05, therefore lot 1 is not statistically significant from the normal distribution and normality can be assumed.

### Lot 3
Lot 3 has a p-value of 0.04168 which is less then 0.05, therefore which means it is statistically significant from the normal distribution and normality cannot be assumed.

## Study Design: MechaCar vs Competition
A linear regression on city and highway fuel efficiency is another statistical study that can quantify how the MechaCar performs against the competition.

#### Metrics to test:
* Horse power, vehicle weight, if it is AWD, RWD, FWD, 4WD
* The null hypothesis being that the horse power, vehicle weight, if it is AWD, RWD, FWD, 4WD doesnt affect the MPG
* Alternative hypothesis being that the horse power, vehicle weight, if it is AWD, RWD, FWD, 4WD does affect the MPG



