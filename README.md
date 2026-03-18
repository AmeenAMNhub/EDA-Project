# Customer Order Behavior Analysis (EDA Project)

## Project Overview

This project analyzes customer order behavior using a Starbucks transactional dataset. The goal is to understand customer spending patterns, ordering habits, and key factors influencing revenue using Exploratory Data Analysis (EDA), Statistical Testing, and Feature Engineering.

The project follows a complete pipeline from raw data → cleaning → visualization → statistical validation → feature engineering → insights.

---

## Objectives

- Understand customer purchasing behavior  
- Identify factors influencing total spending  
- Analyze order patterns over time  
- Evaluate the impact of rewards membership  
- Compare spending across different age groups  
- Create meaningful engineered features  

---


## Data Cleaning and Preprocessing

- Fixed data types (date, time, categorical variables)  
- Handled missing values and inconsistencies  
- Checked and removed duplicates  
- Standardized categorical values  
- Prepared dataset for analysis  

---

## Exploratory Data Analysis (EDA)

- Spending distribution across age groups  
- Average spending by order channel  
- Cart size vs total spend analysis  
- Customer satisfaction distribution  
- Order trends by hour of day  
- Correlation analysis between numerical variables  

---

## Key Visual Insights

- Mobile app users spend more than other channels  
- Cart size strongly influences total spending  
- Customer satisfaction is generally high (ratings 4–5 dominate)  
- Peak orders occur during morning hours  
- Spending varies across different age groups  

---

## Statistical Testing

### Independent T-Test
- Compared rewards members vs non-members  
- Result: Rewards members spend significantly more  

### ANOVA Test
- Compared spending across age groups  
- Result: Spending differs significantly across groups  

### Chi-Square Test
- Tested region vs order channel  
- Result: No significant relationship  

---

## Time-Based Analysis

- Extracted hour, day, and month from order data  
- Identified peak ordering hours  
- Observed lower activity during late-night hours  

---

## Feature Engineering

- spend_category → Low / Medium / High spending  
- large_cart → Identifies large orders  
- morning_order → Orders before noon  
- high_customization → Highly customized orders  
- spend_per_item → Average spend per item  

---

## Final Insights

- Rewards membership strongly increases spending  
- Cart size is the biggest driver of revenue  
- Younger customers show higher spending patterns  
- Mobile app users have higher purchase value  
- Customer satisfaction remains consistently high  
- Morning hours generate the highest order volume  

---

## Recommendations

- Expand loyalty programs to increase revenue  
- Promote mobile app ordering  
- Use bundle offers to increase cart size  
- Optimize staffing during peak hours  
- Target high-spending customer segments  

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  

---

## Conclusion

This project demonstrates a complete end-to-end EDA workflow, providing actionable insights into customer behavior and business performance.

---

## Future Improvements

- Build predictive models  
- Perform customer segmentation  
- Develop recommendation systems  

---



