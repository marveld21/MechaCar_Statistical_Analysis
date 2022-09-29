# MechaCar_Statistical_Analysis
 
## Linear Regression to Predict MPG

![Linear_Regression](https://github.com/marveld21/MechaCar_Statistical_Analysis/blob/main/Resources/Linear%20regression%20to%20MPG.PNG)

- Vehicle length and ground clearance have a non-random amount of variance to the model
- The P value for the model is 5.35e-11 (very close to 0) meaning that it is unlikely to be by chance and that the slope of our model is not 0.
- The model does a good job of predicting mpg of the prototypes, The model has an r² value of 0.7149 which indicates 71% of mpg predictions can be determined by the model.

## Summary Statistics on Suspension Coils

![Total_Summary](https://github.com/marveld21/MechaCar_Statistical_Analysis/blob/main/Resources/total_summary.PNG)

-The total summary shows a variance below the 100 PSI variance requirement.

![Lot_summary](https://github.com/marveld21/MechaCar_Statistical_Analysis/blob/main/Resources/Lot%20Summary.PNG)

-Lot 1 and 2 are well within the 100 PSI variance requirement with relatively small variances.
-Lot 3 has a much higher variance and is actually outside the requirement.

## T-Tests on Suspension Coils

![T-Tests](https://github.com/marveld21/MechaCar_Statistical_Analysis/blob/main/Resources/T-Tests.PNG)

-The first 2 lots are statistically similar with high p-Values
-Lot 3 has a p-Value below 0.05 and will is not similar.

## Study Design: MechaCar vs Competition

ANOVA tests should be done against MechaCars competitors if it results in a p value greater than 0.05 then you can accept the null hypothesis of MechaCar being similar in performance.