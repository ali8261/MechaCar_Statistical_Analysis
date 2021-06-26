# MechaCar_Statistical_Analysis

# Project Overview

This project involves the use of statistics and hypothesis testing to analyze a series of datasets from the automotive industry.
All of the statistical analysis and visualizations is written in the R programming language.


Linear Regression to Predict MPG

![alt text](https://github.com/ali8261/MechaCar_Statistical_Analysis/blob/main/Images/Perform%20linear%20regression.png)


* In the summary output, each Pr(>|t|) value represents the probability that each coefficient contributes a random amount of variance to the linear model. According to our results vehicle length and ground clearance (and Intercept) provide a non-random amount of variance to the linear model of mpg.

* R-square is 0.71 so 71% of the variations in mpg can be explained by changes in the vehicle length, the vehicle weight, the spoiler angle, the drivetrain and the ground clearance. We can consider this linear model as fairly efficient to predict mpg of MechaCar prototypes.

# Summary Statistics on Suspension Coils,

* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

* Lot 1 and Lot 2 are both within design specifications and have hnearly the same exact mean and median. Lot 3 shows the most variance and exceeds the manufacturers specs.

# T-Tests on Suspension Coils

* T-Test all manufacturing lots against the population mean

![alt text](https://github.com/ali8261/MechaCar_Statistical_Analysis/blob/main/Images/T_test.png)

Assuming our significance level is the common 0.05 percent, our p-value of 0.060 is above the significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis, and we can state that the PSI across all manufacturing lots is statiscally similar to the population mean of 1498.78 psi.

# T-Tests each manufacturing lot against the population mean

* Lot1

![alt text](https://github.com/ali8261/MechaCar_Statistical_Analysis/blob/main/Images/Lot1.png)

Here the p-value is below the significance level of 0.05 percent, so we can reject the null hypothesis and conclude that the PSI across the Lot 1 is statistically different from the population mean.

* Lot2

![alt text](https://github.com/ali8261/MechaCar_Statistical_Analysis/blob/main/Images/Lot2.png)

* Lot3

!alt text](https://github.com/ali8261/MechaCar_Statistical_Analysis/blob/main/Images/Lot3.png)

Here both p-values are above the significance level, so we can conclude that the PSI for Lot2 and Lot3 are statistically similar to the population mean.
