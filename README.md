# Exploratory Data Analysis - Fall 2022

## Coronary Heart Disease Analysis

According to the World Health Organization, heart disorders are thought to be the cause of 17.9 million
deaths worldwide each year. Coronary heart disease (CHD) is the most common type of heart disease,
killing approximately 382,820 people annually in the United States. Heart disease cost the US about $229
billion from 2017 to 2018. This includes the cost of health care services, medicines, and lost productivity
due to death. Early cardiovascular disease prognosis can help high-risk individuals make decisions about
lifestyle adjustments that will lessen problems. Our project attempts to understand the major factors
that influence the 10-year risk of Coronary Heart Disease (CHD) and if we can predict the CHD odds by a
simple Logistic Regression model or if there is a requirement for a more complicated model. Initially, we
did variable selection and as per our analysis, the three major factors which influence the risk of CHD are
the age of a person, systolic blood pressure, and gender. We observed that men are at a higher risk of
ten-year CHD compared to women and the risk of CHD increases with an increase in age and systolic
blood pressure. We used logistic regression as our baseline model to predict the 10-year risk of CHD. The
model performed well with only age, cigarettes per day, systolic blood pressure, glucose, and gender as
the predictors. Then we compared this baseline model with a Generalized Additive Model (GAM). GAM
is an adaptation of a linear model that allows us to model non-linear data while maintaining
explainability. The prediction results and the model evaluation metric of both the baseline and the GAM
models are nearly the same. Also, the logistic regression model was much more interpretable with only
a few understandable predictors. Thus, we can conclude that a simple logistic regression model is
enough to predict the 10-year risk of CHD rather than any advanced model. One drawback of this study
is that only 15% of people in the dataset have a ten-year risk of CHD, indicating class imbalance. So, we
plan to add more data in our future analysis to improve the imbalance.
