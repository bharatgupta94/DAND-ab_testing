# DAND-project-3
## Analyze A-B Test Results

####  Performed A/B test on an e-commerce website
Here, goal is to conduct A/B testing on an e-commerce old and new website.

##### Overview
The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Our goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.
(The project used data hosted on Udacity)

Tools Used: Jupyter Notebook
Python Libraries: Pandas, Numpy, Matplotlib, StatsModels, Scipy

##### Key Findings
**A/B Testing:** None of the explanatory variables in the model has significant p_value (all are greater than 0.05) so we fail to reject the null hypothesis (Old page recieved same same or more clicks than New page) and conclude that we don't have sufficient evidence to infer that new page drives more conversions than the old page. 
(P value obtained through z-test is same as p value obtained through Bootstrapped Hypothesis Testing)

**Regreesing Analysis:** Used Logistic Regression to determine conversion rate. In this test, our Null Hypothesis is *conversion rate is equal* i.e., there is no difference in conversion rate of old page and new page and the Alternative is *conversion is not equal* i.e., new page is deriving more or less conversions than old page so this is two tailed test. 
Observation: We fail to reject the null hypothesis and conclude that we don't have sufficient evidence to conclude that new page drives more conversions than the old page.
