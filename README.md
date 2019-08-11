# CaseStudy2_TalentAttrition

This Repository contains (R-code, Power Point, Tableau link, and Knitr) file that will take a companies data and create holestic view of why employees leave or stay at a company. 
Our goal is to give you the necessary tools to concentrate R-code while developing a process to study attrition.
We use R Linear Regression model and then we use Stepwise and allowed it to select best fit model for attrition. Once this model was executed, we examined the p-values of all the variables.
Any p-value that was above 0.05 that we identified, we did farther analysis on that variables, saying it another way, we looked at significant variables that cause attrition.
Here are the value:
lm(AttrAdj ~ OverTime + 
                   MaritalStatus + 
                   JobRole + 
                   Gender + 
                   EducationField +
                   Department + 
                   BusinessTravel + 
                   YearsWithCurrManager +
                   YearsSinceLastPromotion +
                   YearsInCurrentRole + 
                   YearsAtCompany + 
                   WorkLifeBalance + 
                   TrainingTimesLastYear +
                   TotalWorkingYears + 
                   StockOptionLevel + 
                   RelationshipSatisfaction + 
                   PerformanceRating +
                   PercentSalaryHike + 
                   NumCompaniesWorked + 
                   MonthlyRate + 
                   MonthlyIncome + 
                   JobSatisfaction +
                   JobLevel + 
                   JobInvolvement + 
                   HourlyRate + 
                   EnvironmentSatisfaction + 
                   Education + 
                   DistanceFromHome +
                   DailyRate + 
                   Age, data = a)
Once stepwise was used, we examine the p-value and use Tableau to conduct farther analysis to drill down to the root cause of attrition. 
We identified three variables (JobRole, DistanceFromWork, and Age) that causes attrition even though there are many more variables.
This is the tableau link -> https://public.tableau.com/profile/jayson.barker#!/vizhome/DS6306_CS2/Dashboard1
