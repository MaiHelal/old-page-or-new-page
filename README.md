# Analyze website pages 
* we use A/B hypothesis testing in python to help company find out whether the new website landing page has higher users’ convert rate than old page using Pandas and Matplotlib.
* By using regression analysis using two method -- Using loop to similate 10,000 experiment using numpy.random.choice() function and another method is to use StatsModel package to run logistic regression model.
* merge another dataset and measure effect of country factor using sklearn and interpret results with practical reasoning.
Introduction
*Part I - Probability
*Part II - A/B Test
*Part III - Regression
results
*The p-value associated with ab_page is 0.190. The null in c-e part is that there is no difference between the treatment and control group. Alternative hypotheses is that there is difference between between the treatment and control group
*Part II assumes the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%, compared to question c-e,they have different explainory varibale or factor for the result.
*The results appear the p_values for all factors > 0.05 (alfa error) that indicate we Fail to reject the null hypothesis .
*As a final conclousion we can say that Country has no great effect on page conversion in addition, and old page shows aslightly higer conversion rate than the new page , so the decision is to keep the old page.
