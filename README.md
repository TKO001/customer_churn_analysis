# Customer Churn Analysis
Telecom company, **Databel**, runs on a subscription-based model. Reducing customer churn is a priority.

# Objectives
1. Determine Databel’s overall churn rate.

2. Identify key factors influencing customer churn.

3. Analyze demographic, plan, and contract data to understand churn behavior.

4. Recommend actionable strategies to reduce churn and improve customer loyalty.

# Tools and Techniques
1. Microsoft Excel-	Data cleaning, transformation, and visualization

2. Pivot Tables-	Aggregating churn metrics by demographics, plans, and contracts

3. Pivot Charts-	Visualizing churn trends and comparisons

4. Data Binning- Grouping ages and contract durations for deeper insights

# Analysis Process
1. Data Validation- Confirmed no duplicate records in the customer table. Converted churn labels to binary (Churned = 1, Active = 0).

2. Churn Rate Calculation Formula: Churned Customers / Total Customers. Result: Databel lost 1,750 customers, yielding a 27% churn rate.

3. Churn Reason Exploration: Competitors offering better devices and deals are the most common reason for churn. Raises the question: **Is Databel competitive enough?**

4. Demographic Insights: Seniors show the highest churn rate (~40%). Further binning revealed customers aged 79–88 have the highest churn despite being the smallest group. 

5. Plan & Usage Analysis: Customers with unlimited data plans churn more often, typically consuming less than 5GB monthly. Indicates potential mismatch between plan offerings and usage behavior.
   
6. International Plan Impact: States CA, IN, NH have the highest churn among customers with international plans. CA also leads in churn among those without international plans — suggesting regional factors. 

7. Contract Duration & Tenure: Churn decreases with customer tenure. Month-to-month contracts show the highest churn. Customers in their 3rd–4th year on 1-year contracts are more likely to churn than those on 2-year contracts.

### 💡 Key Takeaway
Longer contracts and competitive offers are Databel’s strongest levers to reduce churn. Excel-based analytics provide a foundation for data-driven retention strategies. 

#### Recommendation: Encourage longer-term contracts through targeted marketing. Tailor plans to actual usage patterns. 

###### Credits: Data has been extracted from DataCamp Projects
