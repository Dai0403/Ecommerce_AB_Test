# E Commerce Product Page Design A/B test

Background:
At an e-commerce business, the UX designer worked hard on a new version of the product page. The current conversion rate is about 13% on average throughout the year, and that the team would be happy with an increase of 2%, meaning that the new design will be considered a success if it raises the conversion rate to 15%.


I used the dataset downloaded from Kaggle.
https://www.kaggle.com/datasets/zhangluyuan/ab-testing



Process 

1. Desinging our experiment 
- Creating a hypothesis
- Two tailed test
- Confidence level of 95% (α = 0.05)
- Choosing the variables
  - Control group
  - Teatment group
- Choosing a sample size  (below here please refer to the notebook)
- 4720 based on the effect size, power, α etc 
2. Collecting and preparing the data 
- Checking the distribution of data
- Converted or not
  - 0 - The user did not buy the product during this user session
  - 1 - The user bought the product during this user session
- Sampling 
3. Visualizing the results
4. Testing hypothesis 
5. Drawing conclusion 


Conclusion:
p-value: 0.181 is above our significance level 0.05, meaning that there is no statistically significant difference in the proportions of the outcome between the two groups. In other words, we fail to reject the null hypothesis. The new design couldn't outperform the old design.
Remember, the baseline of conversion rate for the treatement group was set to 13%, and the target value was 15%. If we look at the confidence interval of the treatment group [0.114, 0.133] is 11.6% - 13.3%, which includes the baseline value 13% but not the target value 15%
This is further proof that the new design isn't likely to be an improvement on the old desin. Cheers..


