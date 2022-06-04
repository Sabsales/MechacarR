Mechacar Analysis
 
## Linear Regression to Predict MPG

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Based on the Linear Model, the "Vehicle Length" and "Ground Clearance" with the given data provide statistically that they are non-random variables.

Is the slope of the linear model considered to be zero? Why or why not?
The intereptation of the linear model suggests based on the P-Value(5.35^-11) that the slope of the model is in fact not considered to be Zero. Therefore the null hypothesis would be rejected.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The linear model has an accuracy factor(Multiple R- Squared) of 71%. This percentage while a higher percent would be optimal, the 71% allows for effective prediction of mpg for Mechacar prototypes.



## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The entire data set for the suspension coils PSI shows a variance of 62.29 PSI. This is suitable based on the 100 psi limit.
Lot 1 and Lot 2 both have similar but more consistent variance PSIs that are within the 100 PSI limit. Lot 1 had a var PSI of 0.98 and Lot 2 had a var PSI of 7.46. Lot 3 is the only lot that has a larger variance in both performance and consistancy, having a Variance PSI of 170.28. Because of Lot 3 there is a disproportionate amount of variance caused by Lot 3 at the entire lot level.


## T-Tests on Suspension Coils

Briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.




## Study Design: MechaCar vs Competition

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

What metric or metrics are you going to test?
In my study I would test Owner Satisfaction. As measured by; would the consumer buy the car again or did it live up to their expectations. This is important as it's used in Consumer Reports and other reputable groups. Another metric to test would be fuel economy. This is important based on current fuel prices. 

What is the null hypothesis or alternative hypothesis?
Null: There is no difference regarding the metrics between Mechacars and the competition.
Alternative: Mechacars have higher owner satisifaction and fuel ecomony. 

What statistical test would you use to test the hypothesis? And why?
The two tests required for testing the hypothesis would be the Chi-Squared test because the manufacturer type is catergorical(Dichotomous) and the two consumer satisfaction questions are also Dichotomous. For fuel efficiency there would need to be a two sample t-test because there are two manufacturers because fuel efficiency and MPG are continuous.

What data is needed to run the statistical test?
The data needed would be consumer data of owner satisfaction and actual fuel efficiency overall as recorded by their car computer. I would survey owners from the last 5 years to gather the required data.


