# LITA_CAPSTONE_PROJECT2
------------------
Introduction to the Capstone Project on Data Analysis. The Capstone Project is a comprehensive data analysis initiative that uses datasets to extract meaningful insights and drive informed decision-making. This project integrates various data analysis tools and techniques, specifically Excel, SQL, and Power BI, to showcase a holistic data management and visualization approach.
Throughout the project, we will work with diverse datasets that require cleaning, manipulation, and analysis to uncover trends and patterns. Utilizing Excel, we will perform initial data exploration and analysis, applying functions and pivot tables to summarize key findings. Next, SQL will be employed for more advanced data querying and management, allowing us to retrieve and manipulate large datasets from relational databases efficiently.
Finally, we will harness the power of Power BI to create interactive visualizations and dashboards that present our findings in a user-friendly format. This will enable stakeholders to engage with the data dynamically, facilitating a deeper understanding of the insights derived from the analysis. Overall, this Capstone Project aims to enhance our data analysis skills and demonstrate our ability to effectively utilize analytical tools to solve real-world problems, ultimately contributing to data-driven decision-making processes.

#### Project title: "A Comprehensive Data Analysis Approach: Excel, SQL, and Power BI Integration"


#### CAPSTONE PROJECT OVERVIEW:
----------------------
The Capstone Project is a comprehensive data analysis initiative designed to apply advanced analytical techniques using Excel, SQL, and Power BI. This project aims to harness data from multiple datasets to uncover insights, identify trends, and drive informed decision-making.

#### PROJECT OBJECTIVES:
---------------------
  - Data Collection and Preparation: Gather various datasets relevant to the project's theme, ensuring they are clean, organized, and ready for analysis.
  - Data Analysis Using Excel: Utilize Excel's powerful functions and features, such as pivot tables, formulas, and charts, to conduct exploratory data analysis and derive preliminary insights.
  - Database Management with SQL: Employ SQL to manipulate and query data from relational databases. This includes filtering, aggregating, and joining datasets to prepare for deeper analysis.
  - Data Visualization with Power BI: Create interactive dashboards and visual reports in Power BI, showcasing the findings from the analysis. This allows stakeholders to easily interpret data trends and patterns.


#### EXPECTED OUTCOMES:
---------------------
A comprehensive report detailing the methodologies used, findings, and recommendations based on the analysis. Interactive visualizations that present the data in an engaging format, facilitating better understanding and decision-making. Enhanced skills in data manipulation, analysis, and visualization using industry-standard tools.
This capstone project reinforces analytical skills and provides practical experience handling real-world data scenarios, preparing participants for future roles in data analysis and business intelligence.

#### PROJECT 2: CUSTOMER SEGMENTATION FOR A SUBSCRIPTION SERVICE using EXCEL
-----------------
This project involves analyzing customer data for a subscription service to identify segments and trends. Your goal is to understand customer behavior, track subscription types, and identify key trends in cancellations and renewals. The final deliverable is a Power BI dashboard that presents your analysis.


   - Excel:
     1. Analyze customer data using pivot tables to find subscription patterns.
     2. Calculate the average subscription duration and identify the most popular subscription types.
     3. Create any other interesting reports.

### DATA SOURCES
----------------
The Data sources include the following key points:
   1. Customer_Id: A unique identifier for each customer, linking them to specific orders and other relevant customer details.
   2. CustomerName: The name of the individual or organization that holds the subscription.
   3. Region: The geographical area where the order is placed.
   4. Subscription Type: The category or level of a subscription that a customer purchases, such as "basic," "premium," or "standard."
   5. Subscription Start: The date on which a customer's subscription officially begins.
   6. Subscription End: The date on which a customer's subscription is set to expire unless renewed.
   7. Canceled: A status indicating whether the customer or provider has terminated a subscription before its end date.
   8. Revenue: The total income generated from a customer's subscription over a specific period, often calculated based on the subscription price.
   9. Subscription Duration: The length of time a subscription is active, calculated as the difference between the start and end dates.

These datasets collectively provide a comprehensive view of sales performance, customer behavior, and subscription trends, enabling informed decision-making.


### METRICS OF FOCUS
-------------------------
   1. Subscription Patterns: This comprises of the following;
   -  Subscription Count: The total number of active subscriptions within a given period. 
   Revenue by Subscription Type: The total revenue generated, broken down by each subscription type. This helps identify which subscription types contribute most to the business's revenue.
   -   Average Revenue by type: The average revenue generated per subscription type, is calculated by dividing total revenue by the number of subscriptions to each type. It indicates the average value of each subscription type.
   -   Average Subscription Duration: The average length of time customers remain subscribed, calculated by measuring the duration of subscriptions and averaging them. 
   -   Popular Subscription Type: The subscription type with the highest number of subscribers, indicating which tier or product is most favored by customers. This metric helps understand customer preferences and product popularity.

### TOOLS USED
----------------------
 - Microsoft Excel: 
    - Pivot Tables: Summarizing data and generating insights based on revenue, units sold, and transaction categories.
    - Formulas and Functions: Calculate performance metrics and automate processes like sorting and filtering.
    - Data Visualizations (Charts, Graphs): To create visual representations of trends, comparisons, and key insights. 


### DATA VISUALIZATION
--------------------------
1. ## SUBSCRIPTION PATTERNS
PIVOT TABLE
-------

![subs-count customer](https://github.com/user-attachments/assets/3d739ab3-3ae2-4cec-b256-2fc98fd843aa)

![revenue by sub-type customer](https://github.com/user-attachments/assets/165c983a-4d8e-4661-83b8-1ee120308018)

![average revenue by type customer](https://github.com/user-attachments/assets/1b6d203a-1c62-45b6-9caa-ee9432f740f8)







### Calculate the average subscription duration and identify the most popular subscription types.


 #####   average subscription duration
![average sub-duartion customer](https://github.com/user-attachments/assets/dd96d82f-2902-4247-bc0b-705d19f789e3)

                      formula
                      =AVERAGE(J2:J33788)

 ![AVERAGE SUBSCRIPTIONDURATION,EXCEL](https://github.com/user-attachments/assets/b97eb4aa-7d0c-4ef1-915a-fd2b94020eb2)

-------------------------------------- 
##### most popular subscription types
![mostpopular](https://github.com/user-attachments/assets/c309e2e0-7996-4f54-b93e-d4444dbe215f)

                    Formula
                    =COUNTIF(D:D,"Basic")
                    =COUNTIF(D:D,"Premium")
                    =COUNTIF(D:D,"Standard")


![popularsubchart](https://github.com/user-attachments/assets/5b6dac61-f1de-4cdb-bccb-f8248b7a4f05)

 ### Create any other interesting reports.
 -------
 
    

### PROJECT 1B: CUSTOMER SEGMENTATION FOR A SUBSCRIPTION SERVICE using SQL
---------------------------------
This project involves analyzing customer data for a subscription service to identify segments and trends. Your goal is to understand customer behavior, track subscription types, and identify key trends in cancellations and renewals.
This project uses SQL (Structured Query Language) to analyze and extract meaningful insights from a dataset. The objective is to showcase how SQL can be used to query, manipulate, and transform data to solve business problems, uncover trends, and generate actionable findings. Working with a structured database, various SQL commands and techniques will be applied, including data filtering, aggregation, joins, and subqueries.

#### TOOLS USED
------------------
Microsoft SQL Management Studio

 ### EXPLORATORY DATA ANALYSIS 
Write queries to extract key insights based on the following questions.
------------------------------------
 1. retrieve the total number of customers from each region.
 2. find the most popular subscription type by the number of customers.
 3. find customers who canceled their subscription within 6 months.
 4. calculate the average subscription duration for all customers.
 5. find customers with subscriptions longer than 12 months.
 6. calculate total revenue by subscription type.
 7. find the top 3 regions by subscription cancellations.
 8. find the total number of active and canceled subscriptions.


#### QUERIES AND OUTPUT
--------------

           1.    --------TOTAL NUMBER OF CUSTOMERS FROM EACH REGION--------
                               SELECT 
                               Region, 
                              COUNT(CustomerID) AS TotalCustomers
                              FROM [dbo].[CustomerSales]
                              GROUP BY 
                              Region
                              ORDER BY 
                              TotalCustomers DESC;

![q1 customer](https://github.com/user-attachments/assets/88445b74-e37a-4549-b2d0-d8bcbe4ebef1)


            2. ------POPULAR SUBSCRIPTION TYPE BY THE NO OF CUSTOMER------
                               SELECT 
                                SubscriptionType, 
                                COUNT(CustomerID) AS TotalCustomers
                                FROM [dbo].[CustomerSales]
                                GROUP BY 
                                SubscriptionType
                                 ORDER BY 
                                TotalCustomers DESC
                                
 ![q2 customer](https://github.com/user-attachments/assets/af6ac3f6-a3b8-4fc7-a63d-fda4b0455c9f)

             3. ------FIND THE CUSTOMER WHO CANCELLED THEIR SUBSCRIPTION WITHIN 6 MONTHS----
                        SELECT Customerid, Subscriptionstart, subscriptionend
                        FROM [dbo].[CustomerSales]
                         WHERE DATEDIFF(month, subscriptionstart, subscriptionEND) <=6
                        and subscriptionend IS NOT NULL;

![q3 customer](https://github.com/user-attachments/assets/58af6518-349d-40e4-baae-0ad7f403c084)


              4. -------calculate the average subscription duration for all customers----
                      SELECT AVG(DATEDIFF(MONTH, SubscriptionStart, ISNULL(SubscriptionEnd, GETDATE()))) AS AverageSubscriptionDuration
                      FROM [dbo].[CustomerSales]
                      
 ![q4 customer](https://github.com/user-attachments/assets/8fea368c-bb7c-413c-ab9a-008e71a563c4)
                              

              5.  ---- Customers with subscriptions longer than 12 months-----
                           SELECT customerid, subscriptionstart, subscriptionend
                            FROM [dbo].[CustomerSales]
                           WHERE DATEDIFF(MONTH, subscriptionstart, ISNULL(subscriptionend, GETDATE ())) > 12;
                           
![q5 customer](https://github.com/user-attachments/assets/28c6b558-786f-4383-8fbf-995db3e0b7a9)


                6. ------TOTAL REVENUE BY SUBSCRIPTION TYPE------
                       SELECT SubscriptionType, SUM(REVENUE) AS TOTAL_REVENUE
                       FROM [dbo].[CustomerSales]
                       GROUP BY SubscriptionType;

![q6 customer](https://github.com/user-attachments/assets/5422ae58-0d90-49c2-8d49-f0c37aa77bfa)


                7.  -----top 3 Regions by Subscription cancellations------
                         SELECT TOP (3) [Region], COUNT([CustomerID]) AS Cancellationcount
                          from [dbo].[CustomerSales]
                          where [Canceled] = 'TRUE'
                          GROUP BY [Region]
                          ORDER BY Cancellationcount DESC

![q7 customer](https://github.com/user-attachments/assets/032250bf-d39c-42b1-80e7-01a605e20ffd)


                  8. -----total number of active and cancelled subscription-------
                              SELECT 
                              Canceled, 
                              COUNT (CustomerID) AS TotalSubscriptions
                              FROM [dbo].[CustomerSales]
                              GROUP BY 
                              Canceled

![q8 customer](https://github.com/user-attachments/assets/1405cbf2-9cda-495b-aeed-6fcb846e1677)



