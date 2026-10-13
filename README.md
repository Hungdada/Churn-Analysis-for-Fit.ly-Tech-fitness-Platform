<img width="1118" height="627" alt="report screenshot" src="https://github.com/user-attachments/assets/d6b31ff4-94f2-4842-9bdf-bf5056cbbd4e" />
# Churn-Analysis-for-Fit.ly-Tech-fitness-application
Fit.ly Tech Churn Analysis: A study of customer retention trends using behavioral metrics and support data. Includes data synthesis, churn indicators, and strategic insights. #DataAnalysis #ChurnPrediction #CustomerRetention

## **Project Overview:**

This analysis investigates the upward trend in customer churn at Fit.ly Tech over the last two quarters. By synthesizing account data, support interactions, and user behavior metrics, we have identified key indicators associated with churn to inform our retention strategies. Please note that these findings highlight correlations and behavioral patterns rather than direct causal links.


| Column | Data Type | Description |
|---|---|---|
| `'customer_id'` | Numeric | Unique identifier for the customer, used as the primary key for merging. |
| `'state'` | Character | Geographic location (State) where the customer is located. |
| `'email'` | Character | Customer's email address, used for identification. |
| `'plan'` | Character | The subscription tier chosen by the user (Free, Basic, Pro, or Enterprise). |
| `'plan_list_price'` | Numeric | The standard list price of the subscription plan in USD. |
| `'event_time'` | Datetime | Timestamp of the last recorded user activity or engagement. |
| `'event_type'` | Character | Type of user interaction (e.g., track_workout, watch_video, or no_activity). |
| `'channel'` | Character | Communication method used for support (e.g., Email, Chat, Phone). |
| `'topic'` | Character | The primary subject or category of the customer support ticket. |
| `'ticket_time'` | Datetime | Timestamp when the support ticket was created by the customer. |
| `'ticket_status'` | Numeric | Status code representing the state of the support ticket (Renamed from state). |
| `'resolution_time_hours'` | Numeric | Total time taken to resolve a support ticket, measured in hours. |
| `'churn_status'` | Character | Target variable indicating if the customer has left the service (Yes/No). |


Download the data by clicking these links:

Account info : https://s3.us-east-1.amazonaws.com/talent-assets.datacamp.com/da_fitly_account_info.csv

Customer support : https://s3.us-east-1.amazonaws.com/talent-assets.datacamp.com/da_fitly_customer_support.csv

User activity : https://s3.us-east-1.amazonaws.com/talent-assets.datacamp.com/da_fitly_user_activity.csv
