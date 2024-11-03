# NETFLIX NIGERIA CUSTOMER SEGMENTATION SALES PERFORMANCE 

## ABSTRACT
Abstract
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

~Gather Data: **Collect relevant data from various sources, including customer demographics (age, gender, location), subscription details 
(subscription type, start date, payment history), and behavioral data (usage frequency, average session duration, churn history).**

~ Data Sources: **The dataset used in this analysis was received from an internal
Data Sources from:**

1. **Customer Relationship Management (CRM) software**
2.** Subscription management platform **
3.**  Billing and invoicing systems**
4. **Customer database**
5. ** Sales and marketing automation tools**
   


~ **Data Preparation**

**Data Cleaning: Perform data cleaning to handle missing values, duplicates, and outliers. Ensure data accuracy and consistency across the dataset.**

**Data Transformation: Convert categorical variables into numerical format if necessary, and normalize continuous variables to prepare for analysis.**

~ **Visualizations: Create visualizations (histograms, bar charts, box plots) to identify patterns and distributions in the data, focusing on key 
attributes like subscription type, usage patterns, and churn rates.**


~. **Segmentation Analysis**

Feature Selection: Identify relevant features for segmentation based on the EDA results, such as demographics, usage behavior, and subscription history.

~ **Clustering Techniques: Apply clustering algorithms (e.g., k-means, hierarchical clustering) to segment customers into distinct groups based on selected features.
Determine the optimal number of clusters using methods like the elbow method or silhouette score.**

~ **Cluster Profiling: Analyze the resulting clusters to understand their characteristics, motivations, and behaviors. Develop profiles for each segment 
(e.g., price-sensitive users, high-engagement users).**


~. **Predictive Modeling**

**Churn Prediction: Build predictive models (e.g., logistic regression, decision trees) to identify customers at risk of churning based on their cluster 
membership and historical behaviors.**

~ **Upgrade/Downgrade Prediction: Use similar modeling techniques to predict customers' likelihood of upgrading or downgrading their subscriptions.**

~. Validation and Refinement

** Model Evaluation: Validate the segmentation and predictive models using appropriate metrics (e.g., accuracy, precision, recall) on a holdout dataset.**
**Microsoft excel and Power bi :Used for analysis, data segmentation, visualization, 
data modelling and create interative dashboarding

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
This project adopts a systematic data analysis approach to segment customers of a subscription service offering Basic, 
Standard, and Premium plans.

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

