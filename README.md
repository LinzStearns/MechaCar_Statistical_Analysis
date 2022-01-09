# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![D1_lm_mpg](https://user-images.githubusercontent.com/89872154/148701132-063bed6f-77e4-45a2-9bb1-bc0dff0edf9c.png)


The variables **vehicle_length** and **ground_clearance** provided a non-random amount of variance to the mpg values in the dataset given that the variance values of these variables is above 0. 

The slope of the linear model is not considered to be zero because the p-value of this model is greater than 0.5. The p-value of this linear model is 5.35e-11.

With a Multiple R-squared value of 0.7149, we can conclude that this linear model predicts mpg of MechaCar protoypes effectively or accurately 71% of the time. 

## Summary Statistics on Suspension Coils

![lot_summary](https://user-images.githubusercontent.com/89872154/148702269-14398b22-1ffa-4dd3-9acc-83c1caf6d802.png)

![total_summary](https://user-images.githubusercontent.com/89872154/148702275-09799be5-2a0f-4c89-995f-d25760096aba.png)

As pictured above, we can see that the current manufacturing data meets the design specification of a suspension coil variance under 100 pounds per square inch. This is true for all manufacturing lots in total given the variance of **62.3**. The same can be said of lot 1 and lot 2 given the respective variance values of 0.98 and 7.5. Lot 3, however, does not fit the deisgn specifications with a suspension coil variance of **170.3 PSI**. 

## T-Tests on Suspension Coils

![t_test](https://user-images.githubusercontent.com/89872154/148703108-59957f23-bfe1-40e3-bbac-3a8ec3e60189.png)

The results of the first t-test reveal that the sample mean is not statistically different from the population mean of 1500 PSI with a p-value of 0.06. There is not enough evidence to reject the null hypothesis with a significance level above 0.5. 

![3_t_test](https://user-images.githubusercontent.com/89872154/148703115-56e7424c-dcf2-4a3b-ad07-ae1102fd1ea3.png)

The additional t-tests conducted per lot indicate that Lot 1 & Lot 2 are in line with the first t-test with p-values of 0.6 and 1 meaning these specific lots are not statistically different from the population mean. Conversely, with a p-value of 0.4 in Lot 3, we can reject the null hypothesis that this sample mean and the presumed population mean are not statistically different.

## Study Design: MechaCar vs Competition

In order to remain agile and responsive to market competition, an additional study should be conducted to review the cost of similar cars on the market as a metric.
The null hypothesis of this study is that the average cost of similar cars on the market does not significantly vary from the average cost of MechaCars. 
I would want to evaluate the average cost of several cars, not just two. Given this fact, the best suited statistical test would be the ANOVA which analyzes the variance in means of more than two groups.
I will need the pricing data of multiple car manufacturers including MechaCars such as data from the US Consumer Price Index.
