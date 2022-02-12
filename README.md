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

### **Overall Suummary T-Test**

![T_test(PSI) ](https://user-images.githubusercontent.com/91576834/153687192-638f2a12-c88d-4081-b7aa-3fae00ea47ff.png)

-**The overall summary t-test p-value of (0.4938) is significantly sufficient indicating that the PSI threshold of 1500 is across all manufacturing lots is not different from the population mean.** 

### Manufacturing lot 1

![t_test(lot 1) ](https://user-images.githubusercontent.com/91576834/153687577-a8e15c9f-1483-4260-9080-36603f4ce928.png)

**The p-value of Manufacturing lot 1 indicates strong evidence that lot 1 is similiar to the population mean of 1,500 PSI.**

### Manufacturing lot 2 

![t_test (lot 2)](https://user-images.githubusercontent.com/91576834/153688123-1a29decb-ca25-41c7-a655-9a9a9df1efe5.png)

**The p-value of Manufacturing lot 2 indicates strong evidence that lot 2 is similiar to the population mean of 1,500 PSI.**

### Manufacturing lot 3 

![t_test (lot 3)](https://user-images.githubusercontent.com/91576834/153688240-dd29f118-2522-4595-b347-4696b6d79e88.png)


**The p-value of Manufacturing lot 3 indicates that there is not strong evidence that lot 3 is similiar to the population mean of 1,500 PSI.**


## Study Design: MechaCar vs Competition 

**The statistical models and testing above prove that it would be possible to analyze different production metrics of other vehicles and manufacturing lots. Having similar vehicle data’s would allow comparison between MechaCars productions and competitors. Similar data metrics should include vehicle production and performance specifications. Vehicle data metrics such as miles per gallon (mpg), car weight, and other physical features could be tested to identify vehicle performance and how they correlate with each other.**

## **Hypotheses**

**Both Null and Alternative hypotheses are both required to test properly and buid models. My hypothesis could be derived around the question "Do cars have better mpg in the winter or summer?"** 

 * **Null Hypothesis: It is likely that both seasons have no relation to mpg and there will no sufficient evidence of a relationship.**
 * **Alternate Hypothesis: There will be sufficent evidence of a relationship to reject the null hypothesis.**

## **Testing**

**Similiar multiple linear regression models and t-tests could be used on the vehicle data with a significance level of 0.05%.**

 



