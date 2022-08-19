# MechaCar_Statistical_Analysis

## Deliverable 1 

## Linear Regression to Predict MPG

![Deliverable 1 Screenshot](https://user-images.githubusercontent.com/104873181/185529301-8fd75873-2b32-4d4f-a3d6-5a8bb825c68d.png)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Vehicle length, ground clearance and intercept provide non-random amounts of variance to the mpg values in the dataset based on the p-values calculated for each variable. That means the vehicle length and ground clearance have statistically significant impact on MPG and, because the intercept is statistically significant, there are other variables and factors that contribute to the variation in MPG that have not been included in the model.

Is the slope of the linear model considered to be zero? Why or why not?

The slope of the linear model is not considered to be zero because the p-value of this model is 5.35e-11, which is much smaller than the presumed significance level of 0.05. Therefore we can reject the null hypothesis of the slope being zero.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The linear model has an r-squared value of 0.7149 indicating that approximately 71% of the time the linear model will predict the mpg values effectively, the remaining 29% could be due to instrumental error and/or external factors.

## Deliverable 2

## Summary Statistics on Suspension Coils

A statistical summary tables created using the suspension coil dataset are given below:-

### PSI Statistics Total Summary
![Deliverable 2 Screenshot # 1](https://user-images.githubusercontent.com/104873181/185531030-bb769d2b-6a0c-463e-8d8b-b65eb4bd73c1.png)

### PSI Statistics Lot Summary 
![Deliverable 2 Screenshot # 2](https://user-images.githubusercontent.com/104873181/185531192-0dbe3267-e894-4813-9643-3ec18ea976af.png)

The design specification of MechaCar suspension coils mandate that variance of suspension coils cannot exceed 100 pounds per square inch (PSI)

Looking at our results above, Lot 3 is showing a much larger variance of 170.286 PSI which exceeds the 100 PSI target. Lots 1 and 2 with variances of 0.98 PSI and 7.47 PSI are well within the design specification.

From the data, it is evident that Lot 3 is increasing the overall variance of the dataset to 62.29. Despite the high variance levels of lot 3, the overall variance of the manufacturing data does meet the design specification.

## Deliverable 3:

## T-Tests on Suspension Coils


1. T-test comparing all manufacturing lots against mean PSI

![Deliverable 3 Screenshot # 1](https://user-images.githubusercontent.com/104873181/185533773-eb56ebdc-2fe3-4378-a9f6-40f6b231593d.png)

From the data above, we can see that the p-value of the overall manufacturing lots is 0.06 which is above the significance level of 0.05. This shows deviation from null hypothesis is not statistically significant. 

2. T-test comparing lot 1 against mean PSI

![Deliverable 3 Screenshot # 2](https://user-images.githubusercontent.com/104873181/185533901-7854fcd5-1a20-4f17-aa0e-2b38d35ef135.png)

The true mean for lot one is actually 1500 which is equal to the presumed population mean of 1500 as well. p value of 1 shows that thereis no difference between the population and sample mean

3. T-test comparing lot 2 against mean PSI

![Deliverable 3 Screenshot # 3](https://user-images.githubusercontent.com/104873181/185533944-6fd24c8d-b7f7-48f1-8920-4b9ca169e1eb.png)

For lot 2, outcome is almost similar to lot 1. The mean of the sample come to 1500.2 which is again not statistically different from population mean. p-value greater than 0.05 also validates this.

3. T-test comparing lot 3 against mean PSI

![Deliverable 3 Screenshot # 4](https://user-images.githubusercontent.com/104873181/185533971-e356b651-470c-4535-b34f-42cf04faab26.png)

For lot 3, the mean of the sample calculates to 1496.14. The p-value of this dataset is 0.04168 which is less than our alpha value of 0.05. This shows that the null hypothesis that sample mean is not statistically different different from population mean stands rejected

Overall, it is evident that something was significantly different during the production of Lot 3. The coils produced from this lot have to be inspected and those not meeting quality criteria have to be removed.

## Deliverable 4

## Study Design: MechaCar vs Competition

To quantify our analysis, additional statistical analysis can be performed on overall costs for MechaCars as compared to competitors.

### Hypothesis

Null Hypotheses : MechaCars (sample) have no difference in cost in comparision to competitors (population)

Alternate Hypothesis : MechaCars (sample) have a difference in cost in comparsion to competitors (population)






