# MechaCar_Statistical_Analysis
## Overview
AutosRUs is creating a new Mechacar that is suffering from production troubles. They purpose of this project is to perfomr statistical analysis on the prototype data and look for some insight that may help the manufacturing team solve the production issues. 

## Linear Regression to Prdict MPG

![Linear Regression](https://user-images.githubusercontent.com/116690861/221415224-6bc6479e-d351-4385-815b-bf64a4492bfd.png)

- The vehicle length, and vehicle ground clearance are statistically likely to provide non-random amounts of variance to the model. This means that the vehicle length and vehicle ground clearance have an impact on miles per gallon on the MechaCar prototype.

- The p-Value for this model is 5.35e-11, which is much smaller than the assumed significance level of 0.05%. This shows there is sufficient evidence to reject the null hypothesis, which also tells us that the slope of this linear model is not zero.

- This linear model has an r-squared value of 0.7149, so approximately 71% of all mpg predictions will be determined by this model. We could say that thsi regression model is able to predict the mpg of the MechaCar effectively.

## Summary Statistics on Suspension Coils

![Coils Total Summary](https://user-images.githubusercontent.com/116690861/221418148-501cc035-e871-48dc-8499-5da28d00ecff.png)

- When looking at the data of the three lots combined, the variance of the coils is 62.29 PSI, which is well within the 100 PSI variance requirement.

![Coils Lot Summary](https://user-images.githubusercontent.com/116690861/221418309-9a1213ab-2fb1-4d38-b38a-a43e8d1af2f7.png)

- When looking at each lot individually, it can be observed that Lot 1 and Lot 2 are within the 100 PSI variance requirement. However, Lot 3 show a variance much larger than the other two lots. 

## T-Tests on Suspension Coils

![t test all lots](https://user-images.githubusercontent.com/116690861/221419554-380193d5-0ebf-4d84-a42b-a597dac0411a.png)

- The T-Test for the suspension coils accross all lots has a p-value of 0.06, which means that there is not enough evidence to reject the null hypothesis. The mean of the lots is statistically similar to the population mean of 1500.

![t test lot 1](https://user-images.githubusercontent.com/116690861/221419748-a64e7e7d-527f-4eec-9a28-e4b0434e27ce.png)

- The T-test for lot 1 tells us that the mean is not statistically different from the population mean. With a p-value of 1 ther is not enough evidence to reject the null hypothesis.

![t test lot 2](https://user-images.githubusercontent.com/116690861/221419881-db81c36d-1231-4851-b02b-ac0c2dcbd9ec.png)

- The T-test for lot 2 tells us that the mean is not statistically different from the population mean. With a p-value of 0.6072 ther is not enough evidence to reject the null hypothesis.

![t test lot 3](https://user-images.githubusercontent.com/116690861/221419952-1bbb934d-d18f-4cba-9fa9-479533122433.png)

- he T-test for lot 3 tells us that the mean is statistically different from the population mean. With a p-value of 0.04168 ther is enough evidence to reject the null hypothesis.

## Study Design: MechCar vs Competition
One factor that is going to determine the success of the MechaCar in the market is to determine if it is priced correctly according to its features. 

We can collect data on the MechaCar and comparable models of competitors. This data would include price, fuel efficiency, maintenance cost and safety rating. The null hypothesis would be that the MechaCar is priced correctly based on its features. The alternative hypothesis would be that it is not priced correctly.

To determine if the MechaCar is priced correctly we would use a multiple linear regression model. We can determine wich features have the highest correlation with the price. 
