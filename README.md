# CUSTOMER CHURN ANALYSIS

![image](https://user-images.githubusercontent.com/97131888/183288194-abfb049e-92cb-44e7-a89e-82108c1adb2e.png)

Maven Analytics Challenge - Customer Churn Analysis for a telecommunications company to identify churn risks and help improve customer retention.

## AUTHOR

- [@Renikeji19](https://www.github.com/Renikeji19)

## INTRODUCTION 
Maven Communications is a California-based telecoms company seeking to optimize customer retention and reduce customer churn. Optimizing customer retention is vital to the company as churn is a key driver of EBITDA margin, leads to less revenue and increases competitor market share. Managing churn is also important as it is cheaper to retain existing customers than acquire new customers.

## BUSINESS PROBLEM
In order to uncover the business problems and weak areas to work on to make more profit I outlined some questions to be answered by the data analysis.

•	What are the key drivers of churn?

•	What are the appropriate churn initiatives that should be launched to address the different   churn drivers?


## DATA PREPARATION AND PROCESSING
The dataset consists of 3 CSV files; the customer churn table, a zipcode population table, and the data dictionary.  
The customer churn table consisting of 7,043 rows and 38 columns was merged with the zipcode population table which had 2 columns and 1,671 rows using the Power Query Editor in Microsoft Power BI. Both tables were merged on the zip code column. 


![image](https://user-images.githubusercontent.com/97131888/184004088-bcd8e61f-4993-4df5-869e-61e1b9f41458.png)

![image](https://user-images.githubusercontent.com/97131888/184004189-f2bae03d-f160-4ae1-9d61-f5c39fb7e72c.png)

![image](https://user-images.githubusercontent.com/97131888/184004310-c31f77c7-0a26-4b0e-bb23-59a6a48f4255.png)

After merging, some data cleaning steps were applied to the combined table in the Power Query editor to prepare the data for analysis.

![image](https://user-images.githubusercontent.com/97131888/184004385-348dd7bb-88e1-4167-bd27-337b01d5f1db.png)

  


## DATA ANALYSIS
Customer Profile
The dashboard below shows the full customer profile of the telecommunications company. 

![image](https://user-images.githubusercontent.com/97131888/184005583-68b0ffbf-c6d7-4c29-aa0b-93a7136ed351.png)


The company has a total customer strength of 7,043 and has made a total revenue of $21.37 million. 
1.The analysis reveals that more than 50% of the company’s customers are male, and above the age of 40. 
2. The dashboard also shows that the monthly contract type accounts for >50% of customer subscriptions. 
3. 90.32% of customers subscribe to home phone service with the company. Customers who have spent less than 21 months with the company account for about 41% of the customer base.  
4. The most common payment method is the Bank withdrawal

Churn Analysis

![image](https://user-images.githubusercontent.com/97131888/184005708-dcc9258e-c3ba-49a9-a589-ea4b1c727747.png)

On analyzing the customer data, it was found that 1,869 customers left the business, accounting for 26.54% of Maven’s customer churn.
1.	Of the total churned customers, 1,655 (88.6%) were customers on a monthly contract
2.	The highest churn numbers were seen amongst the oldest customers (60+), as the number of churned customers increases with age. This suggests that older customers are more likely to churn.
3.	 70% of churned customers have been with the company no longer than 20 months. This demography also accounts for the majority of Maven’s customers as indicated in the customer profile dashboard. Consequently, customers with a tenure above 20 months are less likely to leave.
4.	The most frequent reason for churn is competition, which takes a 45% share of the churn rate. The other most common reasons were, dissatisfaction, attitude, and price respectively.


![image](https://user-images.githubusercontent.com/97131888/184026170-478a7dc2-dd44-4655-8b6f-d8b051475fc6.png)
 
5.	The top ten cities with the highest amount of churn account for 22% of total churn. San Diego had the highest amount of churn.
6.	56% of churned customers did not accept any marketing offers, this suggests that customers who do not accept any marketing offers are more likely to churn. 
7.	The analysis also indicates that churned customers were less likely to refer friends or family during their time as customers of the company.
8.	83% of churned customers did not subscribe to an additional technical support plan from the company with reduced wait times.


