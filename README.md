# Customer_Churn_Analysis_Python

Customers are the most important resources for any companies or businessed. What if these customers leave the company due to high charges, better compititor offers, poor customer services or something unknown, which indirectyly shows company's performance. Hence, Customer churn is one of the important metrics for companies to evaluate their performance.

Customer churn rate is the KPI to understand leaving customers. Churn rate represents the percentage of customer that company lost over all the customers at the beginning of the interval.

For example,
If company had 400 customers at the beginning of the month and end with 360, means company's churn rate is 10%, because company lost 10% of the the customer from the base. Companies try to decrease churn rate as 0%.


## 1. Introduction


### Dataset, Features and Target value
Source : https://www.kaggle.com/blastchar/telco-customer-churn ( IBM Sample dataset)

Here, IBM provided customer data for Telco industry to predict churn customer based on demographic, usage and account based information. Main objective is that to analyze churn customer behaviors and develop strategies for customer retention.

Assumption - Here, data source has not provided any information related to time; So I have assumed that records are specific to the perticular month.

Dataset has information related to,

#### Demographic:

- Gender - Male / Female <br>
- Age range - In terms of Partner, Dependent and Senior Citizen

#### Services:

- Phone service - If customer has Phone service, then services related to Phone like;
    - Multiline Phone service
- Internet Service - If customer has Internet service, then services related to Internet like;
    - Online security
    - Online backup
    - Device protection
    - Tech support
    - Streaming TV
    - Streaming Movies

#### Account type:

- Tenure - How long customer is with the company?
- Contract type - What kind of contract they have with a company? Like
    - Monthly bases
    - On going bases - If on going bases, then One month contract or Two year contract
- Paperless billing - Customer is paperless billion option or not?
- Payment method - What kind of payment method customer has?
    - Mailed check
    - Electronic check
    - Credit card (Automatic)
    - Bank transfer (Automatic)

#### Usage:

- Monthly charges
- Total charges

#### Target:

- Churn - Whether customer left the company or still with the company?

### Problem Description

#### Why customers leaving the company?
The reasons behind the customer leaving company could be 
- High charges 
- Better offer from competitor 
- Poor customer service 
- Some unknown reasons

#### How to detect the churn customer? 
- Monitoring usage 
- Analysing complains 
- Analyzing competitors offers

#### How to prevent customers from leaving a company?
Once you detect high risk customers, apply 
- Retention plans 
- Improve customer service


## Conclusion

In this project I Performed Exploratory Data Analysis on IBM Telco dataset to analyze customer churn patterns.
- In terms of gender distribution, 49.53% of our customers are female, while 50.47% are male.
- 26.5% of customers are in churn and have stopped using the company's services
- Developed an insightful Power BI dashboard visualizing key findings, enabling data-driven decision-making and
improving customer retention strategies.
