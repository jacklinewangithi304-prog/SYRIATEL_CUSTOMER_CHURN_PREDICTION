## SYRIATEL CUSTOMER CHURN PREDICTION PROJECT ##

# Project Overview
The project seeks to establish a model that will assist to predict whether a customer will churn or not. We will use binary classiffication to establish the chances of customers churning in the telecommunication industry. The project aims at building a classification model that predicts whether a customer will churn (YES/NO) while identifying the key churn drivers to help support business decisions.

# Business Problem:
Syria Telecommunications company is experiencing a quick loss of customers(customer churn) hence leading to loss of revenue. It is more costly to attract new customers than eetaining existing ones. The company seeks to predict the customers likely to churn in order to take proactive retention actions. Predicting churn also assists Syria Tel in targeting high-risk customers with retantion strategies such as discounts, personalized offers and improved customer service.

# Key Questions:
- Which factors contribute most to churn
- Which customers are more likely to churn?
- Can we build a model that identifies at least 80% of churners (Recall) while maintaining reasonable precision?
- What specific interventions can be recommended based on the model's findings before customers leave?

# Stakeholders
Syria Telecommunications Company. Marketing Department

# Success Criteria
The built model should effectively identify the customers at risk of churn, minimize missed churn cases and provide interpretable insights for business decision making. 

# Project Workflow
| Section | What It Covers |
|---------|----------------|
| 1 | Project Overview|
| 2 | Business Understanding |
| 3 | Data Loading and Understanding|
| 4 | Data Preparation |
| 5 | Building and training three models |
| 6 | Models Evaluation|
| 7 | Choosing the best model |
| 8 | Final summary and recommendations |

# Tech Stack
Python
Pandas
Matplotlib
Seaborn
Scikit-Learn

# EDA
The target variable is binary (True/False), making this a classification problem.

The dataset also shows class imbalance, with fewer customers (14.5%)churning compared to those who stay.
![alt text](image.png)

# Models Used
Logistic Regression (baseline model)
Decision Tree Classifier
Random Forest Classifier (best performing model)

# Evaluation Metrics
Random Rorest model was selected as the best model based on the below evalaution matrix.

 Confusion Matrix
 ROC-AUC Score
 F1-score (important due to class imbalance)

 
# Key Findings
The analysis reveals several key factors that strongly influence customer churn at SyriaTel. One of the most significant predictors is the number of customer service calls. Customers who contacted customer support more frequently were substantially more likely to churn, suggesting dissatisfaction or unresolved issues. Additionally, customers subscribed to the international plan showed a higher likelihood of churning compared to those without it, indicating that this segment may not be receiving sufficient value or may be more price-sensitive.

Usage patterns also played an important role in predicting churn. Customers with higher total daytime minutes and charges exhibited distinct churn behavior, implying that heavy users may be more sensitive to pricing or service quality. Across the models developed, the Random Forest classifier demonstrated the strongest predictive performance, particularly in terms of recall, meaning it was more effective at correctly identifying customers who are likely to churn. This is especially important given the business objective of minimizing missed churn cases. Overall, the findings highlight that both customer experience (service interactions) and usage behavior are critical drivers of churn.
# Recommendations
Based on the findings, SyriaTel should prioritize proactive customer retention strategies targeting high-risk segments identified by the model. Customers with frequent customer service interactions should be flagged for immediate follow-up, with a focus on resolving underlying issues and improving service quality. Enhancing the responsiveness and effectiveness of customer support could significantly reduce dissatisfaction and prevent churn.

Additionally, customers subscribed to international plans should be closely monitored and offered tailored incentives, such as discounted rates or customized packages, to increase perceived value and loyalty. High-usage customers, particularly those with elevated daytime minutes and charges, may benefit from personalized pricing plans or loyalty rewards to reduce the likelihood of switching to competitors. While the model provides valuable predictive insights, it should be used as a decision-support tool alongside business judgment, particularly in cases where prediction confidence is lower. Implementing these strategies can help SyriaTel reduce churn rates, improve customer satisfaction, and ultimately increase long-term profitability.
# Conclusion
While the model provides valuable predictive insights, it should be used as a decision-support tool alongside business judgment, particularly in cases where prediction confidence is lower. Implementing these strategies can help SyriaTel reduce churn rates, improve customer satisfaction, and ultimately increase long-term profitability.
# README link:
https://github.com/jacklinewangithi304-prog/SYRIATEL_CUSTOMER_CHURN_PREDICTION
