# statistic-project

A statistical analysis to evaluate whether a new sales training significantly impacts average transaction value using one-sample t-test.

📝 Project Description
- This project aims to evaluate the impact of a sales training program on the average sales per transaction. From historical data, the company observed that the average sales was $100 per transaction. After implementing a training program for the sales team, a sample of 25 sales transactions was collected to assess whether the training led to a significant change in performance.
  
🎯 Objective
- To determine if there is a statistically significant difference in the average sales after the training, using hypothesis testing (one-sample t-test).

📊 Methodology
- Type of Test: One-Sample t-test (Two-tailed)
- Null Hypothesis (H₀): The mean sales before training = $100
- Alternative Hypothesis (H₁): The mean sales after training > $100
- Significance Level (α): 0.05
- Sample Size (n): 25
- Tools Used: Python, Pandas, Scipy

📈 Results / Insights
- Based on the hypothesis testing, the p-value was greater than the significance level of 5%.
- Therefore, we failed to reject the null hypothesis (H₀).
- This suggests that there is no statistically significant evidence that the sales training led to an increase in average sales.
