# MechaCar_Statistical_Analysis
**Using R to implement linear regression analysis, summary statistics, t-tests, and using a statistical study to compare vehicle performance!** 

## **Linear Regression to Predict MPG**
![Linear Regressions to Predict mpg](https://user-images.githubusercontent.com/91576834/153338219-094fb5f9-0992-46f0-8d7e-33edb7ee414d.png)


**The multiple linear regression model indicates that three of the six variables have coefficients. Based on these coefficients which indicates that they provide a non-random amount of variance to the mpg value in the dataset. These three variables are the intercept itself(mpg), vehicle length, and ground clearance**

![Summary of Linear Regressionn model](https://user-images.githubusercontent.com/91576834/153338243-741bdf0e-0199-425e-91c5-ef15cfb3eb4f.png)


**Based on the summary of the multiple linear regression the p-value (5.35e-11) is much smaller than the assumed significance level of 0.05%. Also, having a r-squared value of 0.71 meaning a 71% of all mpg predications will be correct when using this linear model. However, it is safe to say that the linear model should not be considered zero since there is sufficient evidence.**

## **Summary Statisics on Suspension Coils** 
![total_summary (PSI) ](https://user-images.githubusercontent.com/91576834/153339815-d5fb6d08-da98-46a8-a0ac-fd6b62f4da40.png)

![lot_summary(Manufacturing ](https://user-images.githubusercontent.com/91576834/153339838-a86b3743-74e8-4412-b099-82cb9eb0bcf4.png)

>**The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.**

**Based on the summary statistics, Lot 3 exceeds the allowed variation threshold while Lot 1 and 2 are within the allowed margins of 62 variance**

## T-Tests on Suspension Coils
