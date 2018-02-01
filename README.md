# handwashing-discovery-using-R
Reanalyze the data behind one of the most important discoveries of modern medicne: Handwashing.

Objective: Childbed fever is a deadly diseas affecting women that just have given birth. In the early 1840s
at the Vienna General Hospital, as many as 10% of the women giving birth die from it. I would reanalyze the data
that Dr. Semmelweis used to realize that something was wrong with the procedues at Vienna General Hospital.

Data: yearly_deaths_by_clinics.csv & monthly_deaths.csv (DataCamp)

Packages: tidyverse for data manipulation and ggplot2 for visualization

Summary of findings:
#1. After plotting the proportion of deaths at the two clinics given (yearly_deaths_by_clinic.csv),
I see that the proportion of deaths is constantly much higher in Clinic 1.

The only difference between the clinics was that many medical students served at Clinic 1, while mostly 
midwife students served at Clinic 2. While the midwives only tended to the women giving birth, the medical 
students also spent time in the autopsy rooms examining corpses.

#2. Visualizing the monthly data from Clinic 1 (monthly_deaths.csv), I can see the effect of making handwashing 
obligatory in reducing the proportion of deaths.

#3. A t-test shows that the doctors didn't wash their hands increased the proportion of deaths by between 6.7 and 10
percentage points, according to a 95% confidence interval. The test is statisitcally significant at 95% confidence level.
