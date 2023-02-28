# Predicting Claims Frequency using a Quasi-Poisson Regression Model

This is a project that I worked on in one of my fourth year courses at the University of Waterloo. The aim was to use insurance claims data to predict claims frequency. In other words, the number of times that a customer is going to have an accident and submit a claim in a particular year. Since these accidents are fairly rare (hopefully!), we have an unbalanced data set where the claim count (response variable) is most of the time 0.

I used a Quasi-Poisson regression model for this project. The Poisson distribution is useful to model count data which is what we want. However, I used a Quasi-Poisson regression model which is a generalization of the Poisson regression and is used when modeling an overdispersed count variable. The Poisson model assumes that the variance is equal to the mean, which is not a fair assumption for this project.

For feature selection, I’ve added features one at a time and compared the models’ performance using an ANOVA F test, a significance test of the feature and metrics such as AIC/BIC. As a final validation check, I’ve compared the Gini coefficient on the holdout set of my top models.

Note: You’ll notice that I refer to exposures a lot throughout the script, exposures are essentially how long a customer has been insured by company in a particular year. E.g A customer who has been insured for half a year will have an exposure of 0.5.
