# MechaCar_Statistical_Analysis


Linear Regression to Predict MPG
=====================================
Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?


Vehicle weight, spoiler_angle & AWD provided a non-random amount of variance. The two variables that had the most amount of random variance are ground_clearance and vehicle_length.

Is the slope of the linear model considered to be zero? Why or why not?


Slope is not zero just be looking at the p-value, which is less than 0.05.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
71% of the time the model will predict mpg values correctly


Summary Statistics on Suspension Coils
============================================

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Lot 1 and Lot 2 are both within design specs almost the same  mean and median. Lot 3 shows the most variance and exceeds the manufacturers specs.

T-Tests on Suspension Coils
=========================================

 lot 2 the p-value is  0.6072 which means there is evidence that the suspension coil is different from the population mean  ( see /image )
 
 #Study Design: MechaCar vs Competition
 ===============================================
 
 A metric could be  horsepower, trust of the car, beside mpg and  other interest  go into consumer decision making. We can use our tests to see if our MechaCar is much different from the competiton. We can make a null hypothesis stating that it is not different from the competition and our Alternative would be the opposite. To do this we will need to use our t-test after collecting data from different types of competitor vehicles. Our t-test will be comparing the population of all types of competitor vehicles.



