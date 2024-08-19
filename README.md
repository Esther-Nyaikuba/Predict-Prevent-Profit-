# Predicting customer churn in a Telecommunications Industry
## Business Understanding
### Project Overview
Churn prediction is a strategy that uses customer data to identify clients who are least likely to renew their contracts. 
The significance of initiating this project lies in its potential to address the challenges and enhance Reder Telecom's operations. Here are the top reasons that underline the importance of this project:

Cost Reduction: Acquiring new customers is more expensive than retaining existing ones. Reducing churn can lead to substantial cost savings.
Revenue Growth: A reduction in churn can result in increased revenue as existing customers stay longer and potentially buy additional services.
Customer Satisfaction: Understanding customer behavior and preferences enables Reder Telecom to improve its services, leading to higher customer satisfaction and loyalty.
Competitive Advantage: By leveraging data analytics to predict churn, Reder Telecom can proactively retain customers and gain a competitive advantage over rivals.
Data-Driven Decision-Making: In an industry where data is abundant, using analytics to drive decisions can lead to more informed and effective strategies.

### Business Problem
Reder Telecom is facing an increasing rate of customer churn, which is the percentage of customers who switch to competitors' services or terminate their subscriptions. 
The telecommunications industry is highly competitive, with multiple players offering similar services, and retaining existing customers is becoming increasingly difficult. 

The specific obstacles the company faces include: 
- Intense competition from the many competitors in the market.
- Changing customer Preferences usually because of their need for personalized and high-quality services.
- Pricing pressures from competitors has affected profitability making competitive pricing very difficult to sustain.
- Network quality and performance issues that influence customer satisfaction, which leads to dissatisfaction and churning.
- Difficulty in building  and maintaining customer loyalty.

### Objectives
The objectives of this project are as follows:
Develop a predictive model to identify customers at risk of churning.
Analyze the key factors contributing to customer churn.

## Data Understanding
The dataset available from the company contains the following information:

Customer ID: A unique identifier for each customer.
Name: The name of the customer.
Age: The age of the customer.
Gender: The gender of the customer.
Location: The location or city where the customer is based.
Email: The email address of the customer.
Phone: The phone number of the customer.
Address: The postal address of the customer.
Segment: The customer segment or category to which the customer belongs (e.g., Segment A, Segment B, Segment C)
Purchase History, subscription details, Service Interactions, Payment History, Website Usage,Clickstream Data, Engagement Metrics, Feedback, Marketing Communication,
NPS: The Net Promoter Score (NPS),Churn Label,Timestamp.

### Project Scope
Data Collection: Gather historical customer data from various sources
Data Exploration: Explore the dataset to understand the structure, statistics and get insights.
Data Preprocessing: Scale variables, encode features
Evaluation: Evaluate the model on different metrics like accuracy, precision, etc
Model Development: Build ML models to predict churn from the dataset.
Feature Engineering: Create new features, segment dataset, remove irrelevant features.

### Modeling
Two different models used for this project:
 - LogisticRegression
 - DecisionTreeClassifier
    
Metrics:
 - Accuracy score
 - Prediction score
 - Recall score
 - F1 score

The models have a high accuracy of 96% with a strong ability to identify both positive cases (high recall) and ensure that positive predictions are correct (high precision). 
The high F1 scores indicate a well-balanced model performance, especially in scenarios where both false positives and false negatives are equally important.

### Conclusion
The most important Features:
- The number of service interactions the customer has had through call, email and chat
- The number of times the customer has made Late Payments
- The time spent on the company's website.
- The Net Promoter Score(NPS).