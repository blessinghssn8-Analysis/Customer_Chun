## Customer_Chun
Analytics Portfolio

# Customer Churn Prediction Using Machine Learning

## 1. Project Overview
This project analyzes customer behavior and builds predictive machine learning models to identify customers at risk of churn. It combines exploratory data analysis, feature engineering, and supervised learning techniques to support data-driven customer retention strategies.

The focus is on understanding key drivers of churn and evaluating multiple classification models to determine the most effective approach for predicting customer attrition.

---

## 2. Problem Statement
Customer churn directly impacts revenue, growth, and long-term sustainability. Businesses often lack early warning systems to identify customers likely to leave, resulting in reactive rather than proactive retention strategies.

This project addresses the challenge of predicting customer churn by leveraging historical customer data and machine learning models to classify customers based on their likelihood of churning.

---

## 3. Objectives
- Analyze customer demographics, service usage, and billing patterns
- Identify key factors influencing customer churn
- Build and compare multiple machine learning classification models
- Evaluate model performance using industry-standard metrics
- Provide actionable insights to support retention and engagement strategies

---

## 4. Dataset Description
- **Dataset Type:** Customer churn dataset
- **Observations:** Individual customer records
- **Features Include:**
  - Customer demographics
  - Service subscription details
  - Contract type and tenure
  - Billing and payment information
- **Target Variable:**  
  - `Churn` (Binary: Yes / No)

---

## 5. Exploratory Data Analysis
- Distribution analysis of churn vs non-churn customers
- Analysis of churn rates across contract types and tenure groups
- Examination of service usage patterns related to churn
- Correlation analysis between numerical features
- Identification of class imbalance and outliers

---

## 6. Data Preprocessing & Feature Engineering
- Handling missing and inconsistent values
- Encoding categorical variables
- Scaling numerical features where applicable
- Feature selection based on relevance and correlation
- Splitting data into training and testing sets

---

## 7. Methodology
1. Data ingestion and validation
2. Exploratory data analysis to uncover churn patterns
3. Data preprocessing and feature engineering
4. Model training using multiple classification algorithms
5. Hyperparameter tuning (where applicable)
6. Model evaluation using classification metrics
7. Comparative analysis of model performance

---

## 8. Models Implemented
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier (if applicable)
- Any additional ensemble or baseline models used in the notebook

---

## 9. Model Evaluation & Performance Metrics
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

Performance comparison focused on balancing recall and precision to effectively identify at-risk customers while minimizing false positives.

---

## 10. Key Insights & Findings
- Contract type and tenure are strong predictors of churn
- Customers on month-to-month contracts exhibit higher churn rates
- Billing and payment-related features significantly influence churn behavior
- Ensemble models outperform baseline models in predictive performance
- Feature importance analysis highlights actionable business drivers

---

## 11. Tools & Technologies
- **Programming Language:** Python
- **Environment:** Google Colab
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn

---

## 12. How to Run the Project
1. Clone the repository
2. Open the notebook in Google Colab or a local Jupyter environment
3. Install required dependencies if running locally
4. Execute cells sequentially to reproduce the analysis and results

---

# Customer Churn Analysis – Executive Insights

## 1. Dataset Overview
- **Purpose:** Analyze customer behavior to identify factors driving churn and inform retention strategies.
- **Key Variables:** Customer demographics, tenure, subscription type, services used, billing and payment patterns, support interactions.
- **Target Variable:** `Churn` – indicates whether a customer discontinued service.
- **Business Problem:** High churn leads to lost revenue and increased acquisition costs. Understanding churn drivers enables targeted retention and operational improvements.

## 2. Key Insights
- **Churn Drivers:**
  - Shorter tenure customers are at higher risk of leaving.
  - Month-to-month contracts show significantly higher churn compared to annual or multi-year subscriptions.
  - Lack of bundled services (e.g., internet + TV) correlates with higher churn.
  - Customers reporting frequent service issues or delayed support interactions are more likely to churn.
  - Price-sensitive segments with lower monthly charges churn less if offered flexible payment options.
- **High-Risk Segments:**
  - New customers (≤12 months) on month-to-month plans.
  - Single-service users versus multi-service subscribers.
  - Younger demographic groups with lower engagement.
- **Trends:**
  - Longer tenure correlates with lower churn rates.
  - High engagement (multiple services, consistent usage) is a retention indicator.
  - Promotions and discounts impact churn temporarily but are less effective long-term.

## 3. Business Interpretation
- **Revenue Impact:** High churn directly reduces recurring revenue and increases customer acquisition costs.
- **Retention Implications:** Understanding churn patterns allows for targeted interventions, improving lifetime value.
- **Operational Significance:** Identifying at-risk segments informs customer support prioritization and product bundling strategies.

## 4. Actionable Recommendations
- **Retention Strategies:**
  - Introduce loyalty programs for new customers within the first year.
  - Offer incentives to switch from month-to-month to annual contracts.
- **Customer Engagement Improvements:**
  - Bundle services to increase engagement and reduce churn risk.
  - Proactively reach out to high-risk customers via personalized communications.
- **Pricing & Product Adjustments:**
  - Introduce flexible payment or plan options for price-sensitive segments.
  - Review service quality and support responsiveness to minimize churn triggers.

## 5. Decision-Making Guidance
- **Executive Actions:**
  - Prioritize resource allocation for retention campaigns targeting new and month-to-month customers.
  - Incorporate churn analytics into quarterly strategic reviews.
- **Product & Marketing:**
  - Develop bundle offers and promotions aligned with high-risk segments.
  - Monitor engagement metrics to adjust campaigns dynamically.
- **Operations:**
  - Improve support response times for high-risk accounts.
  - Implement feedback loops to address service issues proactively.
- **Short-Term Priorities:** Identify at-risk customers and implement immediate retention interventions.
- **Long-Term Priorities:** Refine pricing, bundling, and support strategies to sustainably reduce churn and increase lifetime value.

