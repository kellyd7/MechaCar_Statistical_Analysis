# MechaCar_Statistical_Analysis
## Background
AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

In this challenge, you’ll help Jeremy and the data analytics team do the following:

- Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
- Run t-tests to determine if the manufacturing lots are statistically different from the mean population
- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Analysis

### Deliverable 1
![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Linear%20Regression%20(Deliverable%201).png)
![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Linear%20Regression%20Summary%20(Deliverable%201).png)
- The most significant variables in our dataset which show a non-random effect on the MPG of the MechaCar are the Vehicle Length and the Ground Clearance. A linear regression model run on these variables against figures for MPG, resulted in p-values of 2.6x10-12 and 5.21x10-8, respectively. The intercept was also statistically significant, indicating that there are likely other factors, not included in our dataset, that have a strong impact on the MPG.
- The slope of the linear model can not be considered to be zero, as the p-value of 5.35x10-11 is lower than even an extreme level of significance, and thus the null hypothesis must be rejected. This means that the relationship between our variables and the miles per gallon is subject to more than random chance.
- Although there are still unconsidered factors, this model does predict the mpg of the MechaCar prototype with some relative effectiveness. The r-squared value of 0.7149 indicates that the model is 71% accurate.


### Deliverable 2
![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Total%20Summary%20(Deliverable%202).png)
![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Lot%20Summary%20(Deliverable%202).png)
- While the overall variance, as shown in the Total Summary data above, is under 100 psi and meets specifications, there is a problem with one of the individual lots. As shown in the Lot Summary stats, the variance for Lot 3 is well over the acceptable threshold, at 170.

 
### Deliverable 3
![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Suspension%20Coil%20ttest%20(Deliverable%203).png)
- A review of the results of the T-test for the suspension coils across all manufacturing lots shows that they are not statistically different from the population mean, and the p-value is not low enough (0.0603) for us to reject the null hypothesis.

![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Lot1%20ttest%20(Deliverable%203).png)
- A review of the results of the T-test for the suspension coils for Lot 1 shows that they are not statistically different from the population mean, and the p-value is not low enough for us to reject the null hypothesis.

![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Lot2%20ttest%20(Deliverable%203).png)
- A review of the results of the T-test for the suspension coils for Lot 2 shows that they are not statistically different from the population mean, and the p-value is not low enough (0.6072) for us to reject the null hypothesis.

![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Lot3%20ttest%20(Deliverable%203).png)
- A review of the results of the T-test for the suspension coils for Lot 3 shows that they are slightly statistically different from the population mean, and the p-value is just low enough (0.0417) for us to reject the null hypothesis. This lot may be need to be discarded, or at least more closely evaluated.

## Study Design: MechaCar vs Competition
