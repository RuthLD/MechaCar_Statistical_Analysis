# MechaCar_Statistical_Analysis 🚙
Statistical analysis of MechaCar vehicles and a study designed to compare the MechaCar vehicles to competitors.
## Linear Regression to Predict MPG 🚚
![Fig_1.png](https://github.com/RuthLD/MechaCar_Statistical_Analysis/blob/main/Resources/Fig_1.png)
* Fig. 1 is the summary of the linear regression for MechaCar mpg.
  * Based on the Linear regression model there are two values that would have a high level of significance in predicting the mpg of MechaCar prototypes. The vehicle_length and ground_clearance are the variables with a p-value less than 0.05 to several powers. The only other variable that is close to 0.05 is the vehicle_weight. The p-value 0.0776 is not considered significant but should be included in the consideration for mpg since it is so close.
  * The slope of the linear model would be considered as zero due to it being a incredibly small decimal.  
  * The residual standard error is 8.774 which is low for the linear model with 44 degrees of freedom. This indicates that the linear model is decent at predicting the mpg of MechaCar prototypes.
## Summary Statistics on Suspension Coils 🧮
The MechaCar suspension coil design specification dictates that the variance of the suspension coils must not exceed 100 pounds per square inch.
* ![Fig_2 PSI Summary Stats.png](https://github.com/RuthLD/MechaCar_Statistical_Analysis/blob/main/Resources/Fig_2%20PSI%20Summary%20Stats.png)
  * Fig. 2 is the summary statistics for the PSI of MechaCar suspension coils. 
  * The variance for all manufacturing lots is 62.29 based on Fig. 2 which is below the threshold for the design specification of the suspension coils.
* ![Fig_3 PSI Lot Summary Stats.png](https://github.com/RuthLD/MechaCar_Statistical_Analysis/blob/main/Resources/Fig_3%20PSI%20Lot%20Summary%20Stats.png)
  * Fig. 3 is the summary statistics for the PSI of each MechaCar Manufacturing lot.
  * Based on Fig. 3 the Lot 1 and Lot 2 have a small amount of variance, 0.98 and 7.47, in the suspension coils which is significantly below the design threshold. Lot 3 has a variance of 170.29 which is significantly over the design specification threshold. 
  * The variance for all manufacturing lots is affected by the incredibly small variance of Lot 1 and Lot 2 which reduced the impact of the variance for Lot 3. Only Lots 1 and 2 meet the MechaCar design specification for the suspension coil.
## T-Tests on Suspension Coils 📈
Four t.test were performed for the PSI of MechaCar suspension coils. All of the t.test preformed used a population mean of 1,500 pounds per square inch.
* ![Fig_4 All_lots t_test.png](https://github.com/RuthLD/MechaCar_Statistical_Analysis/blob/main/Resources/Fig_4%20All_lots%20t_test.png)
  * Fig. 4 is the t.test for all the manufacturing lots of the MechaCar prototypes.
  * The p-value for all manufacturing lots is 0.06 which is not considered statistically significant, but is very close to normal for the population mean.
* ![Fig_5 Lot_1 t_test.png](https://github.com/RuthLD/MechaCar_Statistical_Analysis/blob/main/Resources/Fig_5%20Lot_1%20t_test.png)
  * Fig. 5 is the t.test for manufacturing lot 1.
  * The p-value for Lot 1 is 1, which is an incredibly low and not considered statistically significant. Lot 1 is reflective of the population mean.
* ![Fig_6 Lot_2 t_test.png](https://github.com/RuthLD/MechaCar_Statistical_Analysis/blob/main/Resources/Fig_6%20Lot_2%20t_test.png)
  * Fig. 6 is the t.test for manufacturing lot 2.
  * The p-value for Lot 2 is 0.61 which is also incredibly low and not considered statistically significant.
* ![Fig_7 Lot_3 t_test.png](https://github.com/RuthLD/MechaCar_Statistical_Analysis/blob/main/Resources/Fig_7%20Lot_3%20t_test.png)
  * Fig. 7 is the t.test for manufacturing lot 3.
  * The p-value for Lot 3 is 0.042 which is statistically significant.
## Study Design: 🚗 MechaCar 🆚 Competition 🚐
* MechaCar can be compared to a competitor on metrics like highway fuel efficiency with the variable mpg using a paired t.test since there are two samples or if more than one competitor data is available an ANOVA test would be effective. The null hypothesis and the alternative hypothesis would be fairly simple. Either MechaCar vehicles have a higher fuel efficiency compared to the competitor or MechaCar vehicles do not have a higher fuel efficiency compared to the competitor. 
Another metric to compare between MechaCar and a competitor would be safety rating which could be categorical data. As categorical data this could be evaluated using a chi-squared test because the differences in the frequency of the categories by group would inform how the safety rating can be compared.
* MechaCar can be compared to a competitor on metrics like highway fuel efficiency with the variable mpg using a paired t.test since there are two samples or if more than one competitor data is available an ANOVA test would be effective. The null hypothesis and the alternative hypothesis would be fairly simple. Either MechaCar vehicles have a higher fuel efficiency compared to the competitor or MechaCar vehicles do not have a higher fuel efficiency compared to the competitor. 
Another metric to compare between MechaCar and a competitor would be safety rating which could be categorical data. As categorical data this could be evaluated using a chi-squared test because the differences in the frequency of the categories by group would inform how the safety rating can be compared.
