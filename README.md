## Effects of HIIT Exercise
### Project Overview:
The aim is to better understand the effects of High Intensity Interval Training (HIIT; a form of cardiovascular exercise, aimed to improve athletic capacity, condition and fat burning). Some of the literature states that HIIT is not an effective means of exercise, while others comment that it is highly effective; however, these effects seem to be dependent on gender. 


### Analysis
#### Scenario 1: 

#### 1.Descriptive statistics for all of the participant demographics and outcome variables 

- 46 (57.5%) of the participants are male, while the remaining 34(42.5%) are female. 
- The average rating of perceived exertion is 34.0946mm, with a standard deviation of 2.55mm, also the minimum rating of perceived exertion is 28.4mm, while the maximum rating is 40.39mm. 
- Likewise, the average time to run 100m is 35.2664 seconds, with a standard deviation of 4.598seconds, also the minimum time to run by the participants is 23.43 seconds, while the maximum time is 48.19 seconds.


#### 2.Select and run the appropriate statistical test(s) 

1. State and justify the statistical test you have chosen 

- Independent Samples t Test will be used because It compares the means of two independent groups to determine whether there is statistical evidence that the associated population means are significantly different.

2. Test the appropriate assumptions
- Assumption of normality of the dependent variable
To test for normality of the Rating of perceived exertion, using Shapiro-Wilk, p-value (0.377) > 0.05 implies that the rating of perceived exertion is normally distributed.
- Also, to test for normality of time to run 100m, using Shapiro-Wilk, p-value (0.305) > 0.05 implies that time to run 100m is normally distributed.
- Assumption of homogeneity of variance
Test for homogeneity of variance for the rating of perceived exertion, p-value (0.485) > 0.05 implies that the assumption of homogeneity of variance is not violated.
- Test for homogeneity of variance for time to run 100m, p-value (0.525) > 0.05 implies that the assumption of homogeneity of variance is not violated.

Run the test

- The 46 male participants (M = 34.79, SD = 2.4) rating of perceived exertion are significantly better compared to the 34 female participants (M = 33.15, SD = 2.48), t(78) = 2.976, p = .004.
 
- There was no significant effect for gender on time to run 100m, t(78) = 0.431, p = .667, despite female participants (M = 35.01, SD = 5.1) slightly attaining higher time to run than male participants (M = 35.46, SD = 4.24).


#### Scenario 2:  

1.Descriptive statistics for all of the participant demographics and outcome variables 

Out of the 80 participants, the majority of the participants 33.8% were between the age 30-39, 23 (28.8%) were between age 40-49, 18(22.5%) were between age 20-29, while the remaining 12(15%) were 50years and above.

The average time to run 100m is 35.2664 seconds, with a standard deviation of 4.598seconds, also the minimum time to run by the participants is 23.43 seconds, while the maximum time is 48.19 seconds.

2.Select and run the appropriate statistical test(s) 

- State and justify the statistical test you have chosen 

One-way Anova, it is used when you have data about one categorical independent variable and one quantitative dependent variable. The independent variable should have at least three levels.

- Test the appropriate assumptions

To test for normality of time to run 100m, using Shapiro-Wilk, p-value (0.305) > 0.05 implies that time to run 100m is normally distributed.

- Assumption of homogeneity of variance

Test for homogeneity of variance for time to run 100m, p-value (0.525) > 0.05 implies that assumption of homogeneity of variance is not violated.

- Run the test 

There was a significant effect in terms of 100m sprint time based on the age group of the participant F(3,76) = 14.03, p < 0.05 

3 Scenario 

1.Descriptive statistics for all of the participant demographics and outcome variables 

66.7% that said are likely to continue the training are male participants, while the remaining 33.3% were female participants.
56.3% that are not likely to continue are females, while the remaining 43.8% are male participants

2.Choose and run the appropriate statistical test(s) 

•	State and justify the statistical test you have chosen 

Pearson Chi Square: It measures the strength of relationship between two categorical variables

•	Test the appropriate assumptions 

The assumptions are satisfied:

The two variables are nominal variable

The two variables consist of two variables

•	Run the test
There was a significant relationship between the likelihood to continue training and gender, X2 (1) = 4.126, p-value = 0.042

4.Scenario 

1.Descriptive statistics for all of the participant demographics and outcome variables 

The average caffeine intake is 6.883mg/kg, with a standard deviation of 1.05mg/kg, also the minimum rating of caffeine intake is 3.90mg/kg, 

while the maximum intake is 12.56mg/kg.

Likewise, the average time they are able to continue exercising is 46.7mins with a standard deviation of 10.88mins, also the minimum time is 23mins, while the maximum time is 76mins.

2.Produce appropriate graphical representation

 


3.Select and run the appropriate statistical test(s) 

•	State and justify the statistical test you have chosen 

Linear regression analysis is used to predict the value of a continuous dependent variable based on the value of another variable (independent).
Assumptions

The two variables are measured at the continuous level

Assumption of normality of the dependent variable:

To test for normality of individual caffeine doses, using Shapiro-Wilk, p-value < 0.05 implies that it’s not normally distributed.

Also, to test for normality of how long they are able to continue exercising, using Shapiro-Wilk, p-value (0.632) > 0.05 implies that it’s normally distributed.


Test of Linearity

 


There is a linear relationship between the two variables between there is a presence of outliers.


•	Run the test

The R2 value (.832) indicates that 83.2% variation in the dependent variable (how long they are able to continue exercising) can be explained by the independent variable (the individual caffeine doses). Hence caffeine dose is appropriate in the prediction of exercise duration. 

Durbin-Watson of 2.055 indicates that there is no autocorrelation detected in the sample.

The regression model predicts the dependent variable (how long they are able to continue exercising) significantly well, F(1,78) = 385.4, p-value < 0.05
The regression equation:

Exercise duration = 111.511 – 9.416 Caffeine doses

When Caffeine doses is 5mg/kg

Exercise duration = 111.511 – 9.416 (5)

Exercise duration = 64.431mins



