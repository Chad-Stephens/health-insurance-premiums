# Determining Predictors for Health Insurance Premiums and Assessing Model Predictive Ability

## Motivation

The subject I’m investigating relates to health insurance which is extremely
important to many people’s lives, especially for those who suffer from significant health
issues. Despite its importance in our society, however, health insurance can become
quite expensive and it’s often difficult to decipher how the total cost a policyholder owes
was calculated. With that, I wish to explore how the total yearly cost can be predicted
based on several key factors (explanatory variables).

## Data Set

The dataset I wish to explore is about medical insurance costs for individuals. It
includes 1,138 observations and 7 variables (Age, Sex, BMI, Children, Smoker, Region,
and Charges). More specifically, there are three continuous variables (Age, BMI, and
Charges), one discrete variable (Number of Children), one binary variable (Smoker),
one nominal variable (Region), and a categorical variable (Sex). The data was originally
collected from a textbook called Machine Learning with R by Brett Lantz. The
dependent variable for this multiple linear regression model will be Charges and the rest
of the variables will be potential independent variables. Of note, both Smoker and
Region will be changed into factored variables (this is not reflected in the Appendix). For
the Smoker variable, 0 = No and 1 = Yes. For the Region variable, 0 = Northeast, 1 =
Northwest, 2 = Southeast, and 3 = Southwest. Additionally, while the main goal of this
model is to make predictions regarding how much an individual is charged with, I’ll also
be looking to see if certain independent variables have a stronger influence on the result
of the dependent variable (i.e. whether certain independent variables have a “better”
linear relationship with the dependent variable compared to others).

# Notes

The project was completed in RMarkdown, so there are both code chunks and written work. For those who are interested in replicating or making improvements to my
work, I have a separate file that only includes the R code. Additionally, the data set used has also been included both as a .csv and .xlsx file.

# References

Boylan, T. A., Cuddy, M. P., & O’Muircheartaigh, I. G. (1982). Import Demand Equations: An Application of a Generalized Box-Cox Methodology. International
Statistical Review / Revue Internationale de Statistique, 50(1), 103–112.
	
Hoffman, C. & Paradise, J. (2008), Health Insurance and Access to Health Care in the United States. Annals of the New York Academy of Sciences, 1136: 149-160.

Iuga, A.O. &  McGuire M. J. (2014). Adherence and health care costs. Risk Manag Healthc Policy, 7:35-44.

Joseph, V. R. (2022). Optimal Ratio for Data Splitting.

Kluender R., Mahoney N., Wong F., & Yin W. (2021). Medical Debt in the US, 2009-2020. JAMA, 326(3):250–256.

Kutner, M. H., Nachtsheim, C. J., Neter, J., & Li, W. (2005). Applied Linear Statistical Models. 5th Edition, McGraw-Hill, Irwin, New York.

Lantz, B. (2013). Machine Learning with R
