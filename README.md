Summary
The analysis focused on understanding customer churn behavior in a telecom company
using a dataset of 7,043 customers with 21 attributes related to demographics, services,
and account details. The objective was to identify key factors driving churn and provide
recommendations for reducing customer attrition.
1. Data Cleaning & Preparation
● Missing or blank values were identified in the TotalCharges column.
○ These blanks corresponded to customers with tenure = 0 months, meaning
new sign-ups who had not been billed yet.
○ They were replaced with 0 to ensure data integrity.
● Data types were standardized, converting columns like SeniorCitizen into
categorical variables for better visualization and modeling.
2. Customer Churn Overview
● Churn Rate: Out of 7,043 customers, approximately 26.5% (1,869 customers)
churned, while 73.5% (5,174 customers) remained.
● This indicates that 1 in 4 customers leaves, highlighting the importance of retention
strategies.
3. Demographic Insights
● Senior Citizens:
○ 16% of the total customer base are senior citizens.
○ 41% of senior citizens churned, compared to 23% of non-senior citizens,
showing a clear risk segment.
● Dependents and Partners:
○ Customers without dependents had a 32% churn rate, while those with
dependents churned at only 15%.
○ Similarly, customers without a partner were 1.6x more likely to churn.
These findings suggest that customers with family ties are more stable and loyal.
4. Service-Related Insights
Several services show strong correlation with churn:
Service Feature Churn % (Yes) Churn % (No)
Internet Service - Fiber Optic 42% DSL: 19%, No Internet: 8%
Online Security 46% No Security: 29%
Tech Support 45% No Tech Support: 31%
Streaming Services 34% 22%
●
Fiber Optic users churn at over double the rate of DSL users, indicating service
quality or pricing issues.
● Lack of Online Security and Tech Support leads to a 15% higher churn rate,
suggesting bundled value-add services could improve retention.
5. Contract Type & Payment Method
● Month-to-Month Contracts:
○ 43% churn rate, significantly higher than yearly contracts (11%).
○ This highlights the need to incentivize long-term plans.
● Payment Method:
○ Electronic Check users churn at 45%, compared to 18-22% for other
payment methods like credit card or bank transfer.
○ Customers paying electronically may lack commitment or prefer flexibility.
6. Financial Factors
● Monthly Charges:
○ Customers paying above $80/month have a 38% churn rate, compared to
15% for those under $40/month.
○ This suggests that pricing is a major driver of churn.
● Total Charges:
○ Long-term, high-value customers have lower churn rates, indicating that
customer lifetime value (CLV) is tied to retention.
7. Business Implications
● Target High-Risk Segments:
Focus on senior citizens, fiber optic users, and month-to-month customers to reduce
churn by offering loyalty rewards, discounts, or value-added services.
● Promote Bundled Services:
Adding Online Security or Tech Support could reduce churn by 15-20%.
● Pricing Strategy:
Consider tiered pricing or discounts for high monthly charge users to address
dissatisfaction.
● Incentivize Long-Term Contracts:
Offering promotions for annual plans could shift customers from high-churn
month-to-month agreements.
