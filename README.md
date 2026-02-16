📊 Key Findings (Insights)
Age Matters: Customers aged 40 to 60 show the highest churn rate, whereas younger demographics are more loyal.

Product Saturation: Customers with 3 or more products have a nearly 100% churn rate, suggesting dissatisfaction with complex service bundles or high fees.

Geographic Risk: Customers in Germany are twice as likely to churn compared to those in France or Spain.

Active Status: Inactive members have a significantly higher exit probability, highlighting the importance of customer engagement.

🛠 Feature Engineering & Technical Deep Dive
To improve the depth of analysis, I created several domain-specific features:

Balance-to-Salary Ratio: Evaluating how much of a customer's income is maintained in their bank account.

Tenure-by-Age: Measuring customer loyalty relative to their life stage.

Technical Note: During analysis, I detected a high correlation (0.89) between Age and Tenure_by_Age, identifying a multicollinearity factor that is crucial for any future predictive modeling.

📈 Visualizations
The analysis includes comprehensive 2x2 subplot visualizations to compare:

Balance Distribution by Churn Status.

Density of Balance (Stayed vs. Exited).

Salary vs. Balance relationship.

Overall Balance Distribution with KDE.

💡 Strategic Recommendations
Targeted Retention: Develop specific financial products or loyalty rewards for the 40-60 age group.

Service Review in Germany: Investigate regional service issues or competitor offers in the German market.

Engagement Programs: Implement re-engagement campaigns for inactive members to reduce churn risk.

Product Optimization: Simplify the experience for multi-product holders to prevent "product overload" churn.
