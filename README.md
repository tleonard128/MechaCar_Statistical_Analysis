# MechaCar_Statistical_Analysis
Data Bootcamp R work for vehicle performance.

## Overview
In this Module I performed statistical analysis using R to provide insights into vehicle performances. 

## Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/49666078/183272738-86f79c15-6850-479b-ad09-38bc232a25a0.png)

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The two variables that provided a non-random amount of variance to mpg were **vehicle_length** and **ground_clearnance** as these two variables had p-values that were both acceptable as seen in the screenshot.

### Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model could not be considered zero becaue of the low p-value of 5.35 x 10^-11. This means that the null hypothesis must be rejected and the relation between the variables and the mpg of the vehicle must be correlated in some way.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
This linear model can be used to effectively predict mpg of MechaCar protypes as the r-squared value indicates a 71.49% accuracy for the model.

## Summary Statistics on Suspension Coils
Total Summary 

![Total Summary](https://user-images.githubusercontent.com/49666078/183274172-7b989ec3-ba6f-4287-92cd-aba9096a45bf.png)

Lot Summary

![Lot Summary](https://user-images.githubusercontent.com/49666078/183274187-2f3203ad-9d72-489b-8a0a-104425a46c4f.png)

### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
As shown in the Total Summary image above, the overall variance is around 62 which meets the 100 pounds per square inch requirement. However when looking at individual lots, Lot 3 does not meet the requirement as the variance in it is around 170.

## T-Tests on Suspension Coils

