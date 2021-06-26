# MechaCar_Statistical_Analysis

# Project Overview

This project involves the use of statistics and hypothesis testing to analyze a series of datasets from the automotive industry.
All of the statistical analysis and visualizations is written in the R programming language.


Linear Regression to Predict MPG

![alt text](https://github.com/ali8261/MechaCar_Statistical_Analysis/blob/main/Images/Perform%20linear%20regression.png)


* In the summary output, each Pr(>|t|) value represents the probability that each coefficient contributes a random amount of variance to the linear model. According to our results vehicle length and ground clearance (and Intercept) provide a non-random amount of variance to the linear model of mpg.

* R-square is 0.67 so 67% of the variations in mpg can be explained by changes in the vehicle length, the vehicle weight, the spoiler angle, the drivetrain and the ground clearance. We can consider this linear model as fairly efficient to predict mpg of MechaCar prototypes.

# Summary Statistics on Suspension Coils,

* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

* Lot 1 and Lot 2 are both within design specifications and have hnearly the same exact mean and median. Lot 3 shows the most variance and exceeds the manufacturers specs.

# T-Tests on Suspension Coils

* T-Test all manufacturing lots against the population mean

![alt text](https://github.com/ali8261/MechaCar_Statistical_Analysis/blob/main/Images/T_test.png)

A review of the results of the T-test for the suspension coils across all manufacturing lots shows that they are not statistically different from the population mean, and the p-value is not low enough (0.0603) for us to reject the null hypothesis. 

# T-Tests each manufacturing lot against the population mean

* Lot1

![alt text](https://github.com/ali8261/MechaCar_Statistical_Analysis/blob/main/Images/Lot1.png)

* A review of the results of the T-test for the suspension coils for Lot 1 shows that they are not statistically different from the population mean, and the p-value is not low enough (1) for us to reject the null hypothesis. 


* Lot2

![alt text](https://github.com/ali8261/MechaCar_Statistical_Analysis/blob/main/Images/Lot2.png)

* A review of the results of the T-test for the suspension coils for Lot 2 shows that they are not statistically different from the population mean, and the p-value is not low enough (0.6072) for us to reject the null hypothesis. 

* Lot3

![alt text](https://github.com/ali8261/MechaCar_Statistical_Analysis/blob/main/Images/Lot3.png)

* A review of the results of the T-test for the suspension coils for Lot 3 shows that they are slightly statistically different from the population mean, and the p-value is just low enough (0.0417) for us to reject the null hypothesis. This lot may be need to be discarded, or at least more closely evaluated.

# Study Design: MechaCar vs Competition

There are many factors that consumers take into consideration when evaluating a car to purchase. However, in a world where ridesharing is becoming more ubiquitous and it's easy and cheap to get around in other people's vehicles, customers looking to purchase a car are looking for more than just a conveyance. They will be looking to buy a car that is an economical means to regularly transport themselves and their items on a reliable, regular basis.

# Metric to test

To narrow down our test, we should evaluate MechaCar's carrying capacity, in cubic inches, in comparison to various competitors' vehicles.

# Null and Alternate Hypothesis

H0: MechaCar prototypes' average carrying capacity is similar to competitor's vehicles in the same vehicle class Ha: MechaCar prototypes' average carrying capacity is statistically above or below that of competitor vehicles.

# Statistical Test Used

The best statistical test for this would be two-sample t-tests.


