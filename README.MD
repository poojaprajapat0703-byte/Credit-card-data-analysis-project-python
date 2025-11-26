Credit Card Data Analysis Case Study
Project Overview
This project conducts an extensive exploratory data analysis on credit card customer data of PSPD Bank, a global bank operating in over 50 countries. 
The goal is to provide meaningful insights into customer spending and repayment behaviors that can help evaluate risk, detect fraud, and optimize marketing and operational decisions.

Business Problem
The credit card industry generates large volumes of transaction data, which can reveal customer preferences, detect fraudulent activity, and reduce chargebacks. PSPD Bank’s CEO, Mr. Jim Watson, tasked the analytics team to:
1. Clean and preprocess the data by handling invalid ages, overspending, and repayment anomalies.
2. Summarize customer counts, product usage, average spends, repayments, and profitability.
3. Identify cities and age groups driving the most spend.
4. Rank top customers by repayment behavior.
5. Visualize patterns across cities, products, and time periods.
6. Build dynamic functions to enable flexible analysis of top customers by different parameters.

Dataset and Project Scale
This project analyzes the following datasets:
1. Customer Acquisition: 100 unique customers with demographic, employment, and credit limit details.
2. Spend Data: 1,500 transaction records across 15 diverse product categories like PETRO, CAMERA, FOOD, etc.
3. Repayment Data: 1,523 records capturing repayment transactions by these customers.
4. The datasets entail a few thousand rows but represent substantial transactional volumes and diverse spending categories, requiring robust data
   cleaning, aggregation, visualization, and dynamic analysis.

Data Cleaning & Preprocessing
1. Ages below 18 were replaced with the mean age value.
2. Spend transactions exceeding customer limits were capped at 50% of respective limits.
3. Repayment amounts exceeding limits were capped accordingly.
4. Data inconsistencies and missing values were addressed using domain knowledge rules.

Methodology & Analysis
1. Utilized Python libraries Pandas and NumPy for comprehensive data handling.
2. Calculated distinct customers, monthly average spend and repayment.
3. Computed monthly profit using 2.9% interest on positive repayment margins.
4. Identified top product categories and highest spending cities.
5. Analyzed age group spend breakdowns.
6. Used Matplotlib and Seaborn for detailed data visualizations illustrating temporal and product-wise trends.
7. Developed user-defined functions to dynamically output top customers by city, product type, and time-period.

Key Findings
1. Distinct Customers: 100
2. Transaction Categories: 15
3. Average Monthly Spend per Customer: ₹234,341.35
4. Average Monthly Repayment per Customer: ₹248,702.65
5. Monthly Profit for PSPD Bank (Interest Earned): ₹923,303.29
6. Top 5 Product Types by Spend:
       a) PETRO: ₹49,863,174.09
       b) CAMERA: ₹41,481,571.96
       c) FOOD: ₹37,773,338.43
       d) TRAIN TICKET: ₹33,067,077.15
       e) AIR TICKET: ₹32,955,445.42
7. City with Maximum Spend: COCHIN (₹73,495,349.26)
8. Spending by Age Groups:
      18-30: ₹88,238,584.55
      31-40: ₹68,525,439.61
      51-60: ₹66,095,358.93
      60+: ₹65,386,460.71
      41-50: ₹60,111,155.25
      <18: ₹16,287,075.14
9.Top 10 Customers by Repayment Amount:
      A61: ₹10,539,142.91
      A60: ₹9,876,290.74
      A13: ₹9,572,000.66
      A22: ₹9,372,561.68
      A21: ₹9,056,336.15
      A43: ₹8,489,871.46
      A45: ₹8,448,334.87
      A12: ₹8,334,760.16
      A48: ₹8,292,416.75
      A14: ₹7,943,268.63

Tools & Technologies
1. Python (Pandas, NumPy) for data processing and cleaning.
2. Matplotlib and Seaborn for data visualization.
3. Jupyter Notebook for analysis execution and documentation.
