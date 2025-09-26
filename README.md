 Credit Card Financial Dashboard

## Objective

The objective of this project is to design an interactive **Credit Card
Financial Dashboard** that provides insights into customer spending
behavior, transaction patterns, and key financial metrics. The dashboard
helps stakeholders monitor revenue streams, track customer segments, and
identify opportunities for growth and risk management.

------------------------------------------------------------------------

## Dataset

The dashboard is built using two datasets:
1. Credit Card Transaction Report: includes details on transaction
amounts, categories, modes of payment, and time periods.
2. Credit Card Customer Report: contains customer demographics
such as age, income group, gender, and spending patterns.

------------------------------------------------------------------------

##  Steps Followed

1.  Data Collection & Preparation
    -   Collected transaction and customer data from credit card
        reports.
    -   Cleaned and transformed the datasets for consistency (handling
        nulls, formatting dates, mapping categories).
2.  Data Modeling
    -   Created relationships between customer and transaction datasets
        using unique customer IDs.
    -   Established measures for revenue, transaction volume, average
        transaction value, etc.
3.  Dashboard Development (Power BI / SQL / Python)
    -   Built KPIs (e.g., total revenue, active customers, average spend
        per customer).
    -   Designed charts to show spending trends by category, gender,
        income group, and payment method.
    -   Incorporated time-based filters (monthly, quarterly) for trend
        analysis.
4.  Insights Extraction
    -   Applied DAX measures and aggregations to identify high-value
        customers and spending categories.
    -   Visualized customer segmentation and their contribution to
        revenue.

------------------------------------------------------------------------

##  Key Insights

1. Overall Performance
- Total Revenue: 57M  
- Total Interest Earned: 8M  
- Total Transaction Amount: 46M  
- Total Transaction Count: 667K  

2. Transaction Trends
- Revenue per quarter remains steady (~14M–14.5M), but transaction counts increased from 163K in Q1 to 173K in Q4.  
- Q4 shows the highest activity, indicating possible seasonal peaks.  

3. Card Category Performance
| Card Category | Revenue | Interest Earned |
|---------------|---------|-----------------|
| Blue      | 47M     | 6.6M            |
| Silver    | 6M      | 0.8M            |
| Gold      | 3M      | 0.38M           |
| Platinum  | 1M      | 0.16M           |

➡️ "Blue cards dominate" in both revenue and interest earned.

4. Usage & Payment Channels
- 'Swipe' transactions generate 36M, 'Chip' 17M, and 'Online' 4M.  
➡️ In-person swipes still dominate; online adoption is relatively low.  

5. Revenue by Expenditure Type
- Top categories: Bills (14M), Entertainment (10M), Fuel (10M), Grocery (9M), Food (8M), Travel (6M).  
➡️ Cards are mainly used for 'recurring and essential expenses'.  

6. Customer Segmentation by Education
- Graduates contribute the most (23M revenue).  
- High School (11M), Unknown (9M), Uneducated (8M).  
- Post-Graduate (3M) & Doctorate (2M) groups contribute least.  

7. Customer Segmentation by Job
- 'Business professionals lead' with 18M revenue.  
- White-collar (10M), Self-employed (9M), Government (8M), Blue-collar (7M), Retirees (5M).  
➡️ Business and white-collar customers are the primary revenue generators.  

8. Customer Demographics (from Customer Report)
- Gender: Male customers generate 31M vs. 26M from Female customers.  
- Age: Highest revenue from 40–50 (14M) and 30–40 (11M) age groups.  
- Marital Status: Married customers contribute 16M vs. 13M from Singles.  
- Income Group: High-income group drives 23M revenue, Medium-income 8M, Low-income 10M.  
- Dependents: Customers with 2–4 dependents contribute the highest revenue (7–9M).  
- States: Top states are TX, NY, and CA (6–7M each).  

9. Key Takeaways
- Blue card customers are the most valuable.  
- In-person swipes dominate but online transactions have growth potential.  
- Business professionals, graduates, and high-income groups drive the bulk of revenue.  
- Married, middle-aged customers with dependents show the strongest engagement.  
- Q4 sees the highest transaction counts, indicating seasonal peaks.  


## Action Items

- Target High-Value Segments:  
  Focus marketing campaigns on 'Blue card customers', 'business professionals', 'graduates', and 'high-income groups', as they drive the bulk of revenue.  

- Seasonal Campaigns:  
  Launch special offers and promotions during 'Q4', when transaction counts peak, to maximize revenue.  

- Channel Optimization:  
  Encourage 'online and chip transactions' by offering cashback or discounts to shift from predominantly swipe usage to more secure and trackable channels.  

- Category-Based Rewards:  
  Expand rewards and discounts for high-spend categories such as "bills, entertainment, and fuel" to increase card usage in these segments.  

- Customer Retention & Loyalty:  
  Design loyalty programs for "married, middle-aged customers with dependents" to retain top spenders and reduce churn.  

- Regional Marketing:  
  Focus efforts on top-performing states (TX, NY, CA) with localized campaigns.  

- Risk Monitoring & Fraud Detection:  
  Strengthen monitoring for unusually high-value transactions, especially from high-income groups, to reduce fraud risk.  


-   Marketing Strategy: Target 'high-income groups' and
    'middle-aged customers' with premium offers.
-   Product Optimization: Expand rewards/discounts for
    'entertainment and travel categories' to boost usage.
-   Digital Adoption: Encourage online payments through cashback and
    incentives.
-   Customer Retention: Design loyalty programs to retain top
    spenders and reduce churn.
-   Risk Monitoring: Track unusually high transactions to strengthen
    fraud detection.
