## Introduction
A/B testing, also known as split testing, refers to a randomized experimentation process wherein two or more versions of a variable (web page, page element, etc.) are shown to different segments of website visitors at the same time to determine which version leaves the maximum impact and drives business metrics. A/B tests are very commonly performed by data analysts and data scientists.

## Project Overview
For this project, I will be working to understand the results of an A/B test run by an e-commerce website. The goal of the project is to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

### Part I - Probability
The probability of conversion is computed. The converted probability for control group is 12.03%, and the converted probability for treatment group is 11.88%. There's no sufficient evidence to say that the new treatment page leads to more conversions since the difference in the conversion probability between the two is minimal.

### Part II - A/B Test
Hypothesis testing was conducted assuming that the old page was better, unless the new one proved to be significantly better at a Type I error rate of 5%. Calculating p-values allowed us to draw conclusions about conversion rates for both pages.

### Part III - A regression approach
The logistic regression is formed on two tailed test (regardless of the direction of the relationship we hypothesize, we are testing for the possibility of the relationship in both directions). To confirm the results obtained in Part II, a regression approach is used.

## Conclusion
Based on the information given, there’s no sufficient evidence to say that the new treatment page leads to more conversions. 
P values for all the variables are higher than 0.05, hence, we fail to reject the null hypothesis. Based on my analysis I would say that, there’s no sufficient evidence to suggest that the new page results in more conversions than old page. So I would suggest to keep the old web page rather than investing money and time on new web page.
