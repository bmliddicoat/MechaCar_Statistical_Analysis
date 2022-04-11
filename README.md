# MechaCar_Statistical_Analysis
* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes

* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots

* Run t-tests to determine if the manufacturing lots are statistically different from the mean population

* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Linear Regression to Predict MPG
### Linear Regression Results
![alt text] ()

* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
In assessing Pr(>|t|) (column represents the p-value associated with the value in the t value column) of all variables/coefficients, it can be determined two provided a non-random amount of variance on mpg within the data set.  The Pr(>|t|) results of vehicle weight, spoiler angle and AWD; would dictate a random amount of variance.

* Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model would not be considered to zero.  This can be determined by taking the p-value of 5.35e-11.  This value is drastically lower than the significance level of 0.05%.

* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The multiple r-squared value is 0.7149.  This would express a 71.5% of predicting the mpg of MechaCar protypes.  This would be lower prediction percentage that a business/stakeholders would want within a study.  Stakeholders may want to see a percentage near 95% for more accurate mpg.

## Summary Statistics on Suspension Coils
### Summary Statistics Table for All Lots
![alt text] ()

### Summary Statistics for Each Production Lot
![alt text] ()

* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Overall, the first test shows that all manufacturing lost show a variance of 62.3.  This would meet the suspension requirements of not exceeding 100 PSI. Although, Lot 3 is showing larger amount of variance of 170 or 70% over the suspension coil requirements.  Lot 3 should be investigated further because it causing large increase to total variance and the lot(3) itself may have issues. 

## T-Tests on Suspension Coils

### T-Test on All Manufacturing lots for PSI Consistency
![alt text] ()

### T-Test on Lot 1
![alt text] ()
### T-Test Lot 2    
![alt text] ()
### T-Test Lot 3
![alt text] ()

* Interpretation and findings for the t-test results. 
For all manufacturing lots to determine PSI consistency, p-value was .06 which greater than .05(95% significance level).  This would mean there is not sufficient evidence to reject a null hypothesis.  The PSI for all lots is statically similar to 1500 PSI with mean 1498.78 PSI.  For lot 1, the 95 percent confidence interval is 1499.71.  This is statically like 1500 PSI.  Lot 2 has 1499.423, which is statically like 1500 PSI.  Lot 3 is 1492.431 PSI which is lower comparison to the other results.  The p-value (.042) shows potential to ignore a null hypothesis.  Overall, Lot 3 once again is showing statistical differences that could be concerning.


## Study Design: MechaCar vs Competition

* What metric or metrics are going to test?
The safety metrics would be tested for the MechaCar and Competition.  These would include data on mock crash of 30 MPH head on.  The results of safety features/metrics such as seatbelts, airbags, impact, survivability, etc. would be used as measurements. 

* What is the null hypothesis or alternative hypothesis?

The Null Hypothesis:  The MechaCar safety ratings is similar to the competitors during one head on collision at 30mph.

The Alternative Hypothesis:  The MechCar safety rating is different than the competitors with one head on collision at 30mph.
* What statistical test would be used to test the hypothesis? And why?

The use of linear regression could be used to differentiate certain safety features as non-random or random variances.  The use of T-Test could help determine mean of safety measurements such as impact and survivability.

* What data is needed to run the statistical test?
A sample size would need to be created.  x will represent the sample size.  An x number of simulated crashes for x amount of each car would need to be completed for each vehicle type.  The data that would be created would also need to be measured against universal standard for safety equipment within vehicles for United States.  This would help determine if x airbag's mean performance is meeting the national standard.  The impact data/survivability would be needed to find results of each vehicle.  
