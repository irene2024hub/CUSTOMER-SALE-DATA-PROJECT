# NETFLIX NIGERIA CUSTOMER SEGMENTATION SALES PERFORMANCE 

## ABSTRACT

**This project focuses on customer segmentation for a subscription-based service that offers three subscription types: Basic, Standard, and Premium. 
By segmenting customers based on their subscription choices, usage patterns, demographics, and other key behavioral factors,
this analysis aims to deliver actionable insights that can enhance customer engagement, retention, and profitability.**

## INTRODUCTION
**In today’s competitive digital economy, customer segmentation is a critical strategy for subscription-based businesses aiming to understand, engage, 
and retain their customers effectively. For services that offer tiered subscription models — typically Basic, Standard, and Premium — understanding
the unique characteristics and preferences of each subscriber type is crucial to optimizing marketing, personalizing user experience, and increasing long-term profitability.**

**This project focuses on developing a data-driven customer segmentation model for a subscription service that provides these three tiers. Customer
segmentation is particularly valuable in this context as it allows businesses to divide their diverse customer base into distinct groups based on
behavioral, demographic, and subscription-specific attributes. Through this process, companies can better understand patterns such as user engagement levels, 
upgrade/downgrade trends, churn risks, and factors influencing customer loyalty.**

**This project aims to provide insights that inform targeted marketing strategies, enhance customer satisfaction, and maximize retention efforts.
Ultimately, customer segmentation enables the subscription service to align its offerings more closely with user needs, driving sustainable growth 
and building a more loyal customer base**

## PROBLEM STATEMENT

**As subscription-based services continue to grow, effectively managing and retaining a diverse customer base has become a significant challenge.
For a subscription service offering tiered plans — Basic, Standard, and Premium — understanding the unique characteristics, preferences, and 
behaviors of each customer segment is critical for driving engagement, reducing churn, and optimizing revenue. However, the lack of detailed
segmentation results in a one-size-fits-all approach that fails to address the varying needs of different customer groups, leading to suboptimal 
resource allocation and missed opportunities for personalized marketing and upselling.**

 **This project aims to address the following core issues:**
 
•	**Identifying Distinct Customer Segments: What are the key characteristics that differentiate customers in each subscription tier (Basic, Standard, Premium),
and how do they vary in terms of demographics, usage patterns, and preferences?**

•	**Understanding Behavioral Drivers: What behavioral factors (e.g., frequency of use, average session duration, customer support interactions) influence a customer’s
likelihood to upgrade, downgrade, or churn? How do these factors vary across subscription tiers?**


•	**Predicting Subscription Tier Changes and Churn: Can we predict which customers are likely to switch tiers or discontinue their subscriptions?
What indicators can help identify at-risk customers within each segment?**

•	**Optimizing Marketing and Retention Strategies: How can the insights from customer segmentation be used to inform more targeted marketing 
strategies, personalized offers, and retention initiatives that cater to each customer group?**

•	**The goal of this analysis is to develop a comprehensive customer segmentation model that categorizes customers based on relevant factors
and provides actionable insights. By understanding and addressing the specific needs of each segment, the subscription service can enhance user experience,
increase retention, and maximize revenue, ultimately achieving a more sustainable and customer-centric growth strategy.**

## PRIMARY OBJECTIVES


**This customer segmentation analysis for a subscription service with Basic, Standard, and Premium plans aims to achieve the following primary objectives:**

1. #### Identify Distinct Customer Segments ####

**Analyze customer data to identify unique segments within each subscription tier.**

**Define each segment based on demographic, behavioral, and subscription-related attributes to understand the core differences among Basic, Standard, 
and Premium users.**

2. #### Determine Key Behavioral Drivers ####

**Identify and analyze key behavioral factors (e.g., frequency of use, session duration, engagement patterns) that influence customer choices within 
and across subscription tiers.**

**Understand which behaviors are associated with higher customer satisfaction, loyalty, or potential for upgrading/downgrading.**

3. ##### Predict Subscription Changes and Churn ####

**Develop predictive models to identify customers likely to upgrade, downgrade, or churn based on historical data.**

**Determine the most significant predictors of churn and switching behavior for proactive retention efforts.**

4. #### Optimize Marketing and Retention Strategies ####

**Use insights from segmentation to create targeted marketing and retention strategies tailored to each segment’s preferences, needs, and behaviors.**

**Provide recommendations for personalized offers, content, or services to improve customer experience and drive higher engagement across subscription types.**

5. #### Enhance Customer Lifetime Value (CLV) across Segments ####

**Quantify the Customer Lifetime Value (CLV) for each segment and identify opportunities to maximize it.**

**Explore ways to encourage upselling, cross-selling, and loyalty strategies that cater to each segment’s potential value.**

6. #### Develop a Scalable Segmentation Framework ####

**Create a scalable segmentation framework that can be periodically updated with new data.**

**Ensure that the model adapts to evolving customer preferences and remains relevant for long-term strategic use.**

**By achieving these objectives, the project aims to provide actionable insights that enable the subscription service to drive customer-centric growth, improve retention rates, and maximize the lifetime value of each segment.**

## DATA MANIPULATION
 The methodology comprises the following key steps:

~. **Data Collection**

~  **Gather Data**: **Collect relevant data from various sources, including customer demographics (age, gender, location), subscription details 
(subscription type, start date, payment history), and behavioral data (usage frequency, average session duration, churn history).**

~ **Data Sources**: **The dataset used in this analysis was received from an internal
Data Sources from:**

1. **Customer Relationship Management (CRM) software**
2. **Subscription management platform **
3.**  Billing and invoicing systems**
4. **Customer database**
5. **Sales and marketing automation tools**
   


~ **Data Preparation**

**Data Cleaning: Perform data cleaning to handle missing values, duplicates, and outliers. Ensure data accuracy and consistency across the dataset.**

**Data Transformation: Convert categorical variables into numerical format if necessary, and normalize continuous variables to prepare for analysis.**

~ **Visualizations: Create visualizations (bar charts, Slicers, pivot table chart) to identify patterns and distributions in the data, focusing on key 
attributes like subscription type, usage patterns, and churn rates.**


~. **Segmentation Analysis**

~ **Feature Selection**: **Identify relevant features for segmentation based on the EDA results, such as demographics, usage behavior, and subscription history**.


~ **Cluster Profiling: Analyze the resulting clusters to understand their characteristics, motivations, and behaviors. Develop profiles for each segment 
(e.g., price-sensitive users, high-engagement users).** Also determine total number of  distinct  customer across the regions**


~. **Predictive Modeling**

**Churn Prediction: Build predictive models (e.g., logistic regression, decision trees) to identify customers at risk of churning based on their cluster 
membership and historical behaviors.**

~ **Upgrade/Downgrade Prediction: Use similar modeling techniques to predict customers' likelihood of upgrading or downgrading their subscriptions.**

~. **Validation and Refinement**

**Model Evaluation: Validate the segmentation and predictive models using appropriate metrics (e.g., accuracy, precision, recall) on a holdout dataset.**




## ANALYSIS QUESTION ##

•	**Calculate the average subscription duration** 
•	**Identify the most popular  subscription type**

 *  **Write queries to extract key insights based on the following questions**.
   *  **Retrieve the total number of customers from each region.**    
  * **Find the most popular subscription type by the number of customers.** 
*  **Find Customers who canceled their subscription within 6 months.** 
* **Calculate the average subscription duration for all customers. **
* **Find customers with subscriptions longer than 12 mOnths**
* **Calculate total revenue by subscription type.**
* **Find the top 3 regions by subscription cancellations.**
* **Find the total number of active and canceled subscriptions.**



  ## APPROACH ##
  
  ### ANALYSIS TOOLS USED;

**Analysis tools Usedfor r analysis, data segmentation, visualization,** 
data modelling and create interative dashboarding** are:

* **MICROSOFT EXCEL
* ** SQL SERVER
*  **POWER BI  DESKTOP
  

 *  
### MICROSOFT EXCEL PIVOT TABLES SUMMARY REPORT ###

![image](https://github.com/user-attachments/assets/e818e9d9-d2c2-479f-bfdb-4ca4e78d8aab)


![image](https://github.com/user-attachments/assets/eec5c898-c09c-4696-953b-c94145fb9597)

![image](https://github.com/user-attachments/assets/e97f860d-9919-4f89-aa01-8d6731c360f0)


### SQL QUERIES REPORTS  ###

![image](https://github.com/user-attachments/assets/90482a47-2933-4777-a19c-1f099f6a262b)

![image](https://github.com/user-attachments/assets/45cf5b49-4f09-440b-99ab-469bd8652a70)

![image](https://github.com/user-attachments/assets/ca848c83-5c22-426c-971a-12243576cffb)

![image](https://github.com/user-attachments/assets/c94e3878-988d-4b9d-b1fc-4030bc54c308)

![image](https://github.com/user-attachments/assets/41ec7cc1-6e47-47f8-8a80-aa85d94d0494)

![image](https://github.com/user-attachments/assets/d9bae11e-a05e-40bc-a823-edb83eee8e46)

![image](https://github.com/user-attachments/assets/ccb3eac5-c0b5-497d-947e-a3ff8fed0f0e)

![image](https://github.com/user-attachments/assets/11c0ca0b-52e6-491c-8029-a1d294181625)

![image](https://github.com/user-attachments/assets/4ad5089b-62d7-421c-9e95-f9ef9e1b0e0f)

## Dataset importation process  from SQL SERVER to Power BI 

![image](https://github.com/user-attachments/assets/fe2b6814-5778-4221-96ee-c5fda2e69c6b)

![image](https://github.com/user-attachments/assets/f06312f4-2062-44c3-bbe9-5f3857b1173c)

## Quality of Dataset checked

![image](https://github.com/user-attachments/assets/71a72f07-c462-46ee-ba0e-285fa0c7c3d7)

## CONDITIONAL COLUMNS AND MEASURE WERE CREATED TO BUILD  MORE INSIGHTFUL REPORT 

![image](https://github.com/user-attachments/assets/0ffe3391-34d4-486a-87ab-0a3287005119)

![image](https://github.com/user-attachments/assets/1cdfbf54-ca2a-4f46-970d-66c15b39bb02)

              ## GENERAL DASHBOARD
              
![image](https://github.com/user-attachments/assets/4211d7fc-3389-47cc-9936-0bd1c9c4d1f8)

        

 ## SUBSCRIPTION PATTERN WITH THE HIGHEST TOTAL REVENUE (BASIC)

![image](https://github.com/user-attachments/assets/365c4067-9e4c-4e2c-a207-b40ab65561e6)


## SUBSCRIPTION PATTERN WITH THE LOWEST TOTAL REVENUE (STANDARD)

![image](https://github.com/user-attachments/assets/0c2f010c-9f00-45a7-a5dd-0764790c9357)


## OVERVIEW OF TOTAL NUMBER OF CANCELATION STATUS FOR THE YEAR

![image](https://github.com/user-attachments/assets/80634898-c6df-4a4f-b02b-5642d88de174)


# OVERVIEW OF TOTAL NUMBER OF ACTIVE SUBSCRIBERS FOR THE YEAR

![image](https://github.com/user-attachments/assets/9c4a1def-b4c6-46dd-a81c-f16be9afd8d1)


## REGION WITH THE HIGHEST SALES REVENUE ( EAST)

![image](https://github.com/user-attachments/assets/d8cd1d05-ea24-4025-8159-d2e52777ec5a)


##   MONTHLY  AND QUARTLY SALES DASHBOARD

 ![image](https://github.com/user-attachments/assets/6ab6a42b-9c96-492a-b705-f965c06d5a50)
   
## 1ST QUARTER RECORED THE HIGHEST SALES REVENUE

![image](https://github.com/user-attachments/assets/45f2e234-8f85-4568-a716-c5f314cb2b30)

## 4TH QUARTHER RECORDED LOWEST TOTAL SALES REVENUE

![image](https://github.com/user-attachments/assets/d772803d-7cfb-416c-9fb1-ac33e8430733)

