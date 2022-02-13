# MechaCar_Statistical_Analysis
## Background
AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

In this challenge, you’ll help Jeremy and the data analytics team do the following:

-Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
-Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
-Run t-tests to determine if the manufacturing lots are statistically different from the mean population
-Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Analysis

### Deliverable 1
![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Linear%20Regression%20(Deliverable%201).png)
![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Linear%20Regression%20Summary%20(Deliverable%201).png)
-The most significant variables in our dataset which show a non-random effect on the MPG of the MechaCar are the Vehicle Length and the Ground Clearance. As indicated by the yellow arrows in the image above, a linear regression model run on these variables against figures for MPG, resulted in p-values of 2.6x10-12 and 5.21x10-8, respectively. The intercept was also statistically significant, indicating that there are likely other factors, not included in our dataset, that have a strong impact on the MPG.
The slope of the linear model can not be considered to be zero, as the p-value of 5.35x10-11, indicated by the orange arrow above, is lower than even an extreme level of significance, and thus the null hypothesis must be rejected. This means that the relationship between our variables and the miles per gallon is subject to more than random chance.
Although there are still unconsidered factors, this model does predict the mpg of the MechaCar prototype with some relative effectiveness. The r-squared value of 0.7149, highlighted in the purple box, indicates that the model is 71% accurate... though it could probably do better.


### Deliverable 2
![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Total%20Summary%20(Deliverable%202).png)
![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Lot%20Summary%20(Deliverable%202).png)


### Deliverable 3
![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Suspension%20Coil%20ttest%20(Deliverable%203).png)
![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Lot1%20ttest%20(Deliverable%203).png)
![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Lot2%20ttest%20(Deliverable%203).png)
![This is an imgae](https://github.com/kellyd7/MechaCar_Statistical_Analysis/blob/main/Images/Lot3%20ttest%20(Deliverable%203).png)


## Study Design: MechaCar vs Competition
