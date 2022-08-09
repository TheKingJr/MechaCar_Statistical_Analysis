# MechaCar Statistical Analysis Challenge 15

## Overview of Project

The premise of this project was to assist the manufacturing team determine what is the cause of their production progress trouble regarding their newest AutoRUs' prototype, MechaCar. In order to achieve this task, multiple linear regression analysis was performed to identify which variables in the dataset predict the mpg of MechaCar prototypes, summary statistics on the PSI of the suspension coils was collected, t-tests were run to determine if the manufacturing lots were statistically different from the mean population, and a statistical study to determine how MechaCar performs against other manufacturers vehicles. Please see below for the analysis deliverables.

- Deliverable 1: Linear Regression to Predict MPG

- Deliverable 2: Summary Statistics on Suspension Coils

- Deliverable 3: T-Test on Suspension Coils

- Deliverable 4: Design a Study Comparing the MechaCar to the Competition

## Results

### Linear Regression to Predict MPG

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- From the summary statistics, vehicle length and ground clearance provided the greatest non-random amount of variance. Indicating that these design features influence the MechaCars performance the most. 

Is the slope of the linear model considered to be zero? 
- No, the overall influence of the parameters is positive. This is shown when producing the linear regression with all 6 variables. Additionally looking at the y-intercept, it can be observed that it is negative which reveals that the slope is positive. 

Does this linear model predict mpg of MechaCar prototypes effectively?
- I would say so, it provides a lot of valuable insight and there are a couple of variables that have a direct impact in predicting mpg. The two being vehicle length and ground clearance. 

### Summary Statistics on Suspension Coils

The design specifications for MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 PSI. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually?

In total, the MechaCar suspension coils meet the 100 PSI variance threshold. However, when it comes to individual lots, only Lot 1 and Lot 2 meet the 100 PSI criterion. Lot 3 is out of spec when it comes to variance and an investigation by the manufacturing team should be conducted on Lot 3 to see what is happening and how they can correct the issue. 

### T-Tests on Suspension Coils

For all t-tests on the suspension coils, there is not sufficient evidence to reject the null hypothesis if the assumed significance level is 0.05 percent. Additionally for all t-tests, the means for the sampled manufacturing lots and population mean of 1500 PSI are statistically similar. However, lot 3, introduces the biggest deviations from the population mean of 1500 PSI. This further exemplifies the necessity to investigate the manufacturing practices at lot 3. 

### Study Design: MechaCar Vs Competition

An ideal statistical study design, in my opinion, for consumers would measure the MechaCar against competition in terms of cost, mpg for both city & highway efficiency, maintenance cost, and safety rating. 

H0: There is no difference in the mean between MechaCar and the competition/ slope is zero (applicable for maintenance cost)
Ha: There is a difference in the mean between MechaCar and the competition/ slope is not zero (applicable for maintenance cost)

The statistical test I would implement for cost, mpg, and safety rating would be the two-sample t-Test. The reason for this is that I would like for the customer to really be able to differeniate between vehicles. For example, if the vehicles are similar in terms of performance, then they can simply decide based on whichever vehicle they think looks best or based on brand preference. 

The second statistical test I would implement is linear regression for maintenance. This is an important test that most customers often don't think about, but if they knew about it I'm almost certain it would definitely influence their decision. If MechaCar is favorable in this statistical test, it would definitely reflect in their sales. 

Lastly, if desired, another success metric (sales) that could be tested between MechaCar and its competition is amenities. This would require an A/B statistical analysis and the null hypothesis would be checking if sales increase based on certain amenities being equipped on the vehicle such as a backup camera, etc. This would be a good way to predict how MechaCar would perform against its competitors based off of amenities and whether they should be added to the vehicle as well. 


