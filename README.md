# Yulu-Hypothesis_Testing
* Yulu is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, Yulu provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting.

* Yulu zones are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient!

* Yulu has recently suffered considerable dips in its revenues. They have contracted a consulting company to understand the factors on which the demand for these shared electric cycles depends. Specifically, they want to understand the factors affecting the demand for these shared electric cycles in the Indian market.
____________________________________________________________________________
Column Profiling:
● datetime: datetime
● season: season (1: spring, 2: summer, 3: fall, 4: winter)
● holiday : whether day is a holiday or not
● workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
● weather:
o 1: Clear, Few clouds, partly cloudy
o 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
o 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain +
Scattered clouds
o 4: Heavy Rain + Ice Pellets + Thunderstorm + Mist, Snow + Fog
● temp: temperature in Celsius
● atemp: feeling temperature in Celsius
● humidity: humidity
● windspeed: wind speed
● casual: count of casual users
● registered: count of registered users
● count: count of total rental bikes including both casual and registered
____________________________________________________________________________

1. Define the Problem Statement, Import the required Libraries and perform
Exploratory Data Analysis.
a. Examine dataset structure, characteristics, and statistical summary.
b. Identify missing values and perform Imputation using an appropriate method.
c. Identify and remove duplicate records.
d. Analyze the distribution of Numerical & Categorical variables, separately
e. Check for Outliers and deal with them accordingly.

2. Try establishing a Relationship between the Dependent and Independent Variables.

3. Check if there any significant difference between the no. of bike rides on Weekdays
and Weekends?
a. Formulate Null Hypothesis (H0) and Alternate Hypothesis (H1)
b. Select an appropriate test -
c. Set a significance level
d. Calculate test Statistics / p-value
e. Decide whether to accept or reject the Null Hypothesis.
f. Draw inferences & conclusions from the analysis and provide recommendations.

4. Check if the demand of bicycles on rent is the same for different Weather
conditions?
a. Formulate Null Hypothesis (H0) and Alternate Hypothesis (H1)
b. Select an appropriate test -
c. Check assumptions of the test
i. Normality
ii. Equality Variance
d. Set a significance level and Calculate the test Statistics / p-value.
e. Decide whether to accept or reject the Null Hypothesis.
f. Draw inferences & conclusions from the analysis and provide recommendations.

5. Check if the demand of bicycles on rent is the same for different Seasons?
a. Formulate Null Hypothesis (H0) and Alternate Hypothesis (H1)
b. Select an appropriate test -
i. Hint: One-way ANOVA test
c. Check assumptions of the test
i. Normality
ii. Equality Variance
d. Set a significance level and Calculate the test Statistics / p-value.
e. Decide whether to accept or reject the Null Hypothesis.
f. Draw inferences & conclusions from the analysis and provide recommendations.

6. Check if the Weather conditions are significantly different during different Seasons?
a. Formulate Null Hypothesis (H0) and Alternate Hypothesis (H1)
b. Select an appropriate test -
c. Create a Contingency Table against ‘Weather’ & ‘Season’ columns
d. Set a significance level and Calculate the test Statistics / p-value.
e. Decide whether to accept or reject the Null Hypothesis.
f. Draw inferences & conclusions from the analysis and provide recommendations.
