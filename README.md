# udacity_ab_testing
For this project, I worked to implement an A/B test for an e-commerce website and understand the results. The goal was to decide if the company should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

The dataset contains information on each user, time, treatment group, conversion and country. The approach was to assess and clean the dataset and run the A/B test.

## A/B Test:

The test was performed by using a Logistic Linear Regression model to predict the probability of an individual conversion. 

The null hypothesis was: The conversion rate of the old page is greater or equal to the conversion rate of the new page.  𝑝𝑜𝑙𝑑  >=  𝑝𝑛𝑒𝑤
The alternative hypothesis was: The conversion rate of the new page is greater than the conversion rate of the old page.  𝑝𝑛𝑒𝑤  >  𝑝𝑜𝑙𝑑

I performed a sampling distribution for the difference and calculated the z- and p-value. In addition a regression model was used to calculate the p-value and find possible differences based on the country of the users.

