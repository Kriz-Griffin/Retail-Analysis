# Retail-Analysis
#### This data visualization project focuses on analyzing customer satisfaction in a retail environment using detailed transaction-level data. The dataset includes customer demographics, purchase behavior, satisfaction ratings, and return status across various store types and locations. 

#### Tools used : 
* **Data Cleaning :** _Excel and Power Query_
* **Visualization :** _PowerBI_

<Details> 
<summary> About the data </summary>
1. Transaction_ID – A unique identifier assigned to each purchase transaction.
2. Customer_Name – The name of the customer who made the purchase.
3. Customer_Age – The age of the customer at the time of the transaction.
4. Store_Location – The geographic location or name of the store where the purchase occurred.
5. Store_Type – The classification of the store (e.g., Urban, Rural, Suburban).
6. Product_Category – The broader category under which the purchased item falls (e.g., Groceries, Clothing).
7. Product_Name – The specific name or brand of the purchased product.
8. Quantity – The number of units of the product purchased.
9. Purchase_Amount – The total monetary value of the transaction.
10. Discount_Applied – The discount rate applied to the transaction (in decimal or percentage).
11. Payment_Method – The mode of payment used by the customer (e.g., Credit Card, Cash).
12. Purchase_Date – The date when the transaction took place.
13. Customer_Satisfaction_Rating – A numeric score representing the customer's satisfaction with the purchase.
14. Return_Status – Indicates whether the product was returned or not (e.g., Yes, No, Returned).
</Details> 

<details> <summary>Preproecessing the data! </summary>

In this **Customer_Age** have so many missing values, **Quantity** had so many null values and 0 as value, **Discount_Applied** had so many missing values, **Purchase_Date** had a non-unifrom format of date and **Return_status** also has non-unifrom datas.
By using Excel and PowerQuery, we can rectify these issues.
  
* Customer_Age - using "Fill" the values are filled from top to bottom, since there are nearly 50% of null values in the data, filling with Mean or median is not preffered.
* Quantity - using excel, I have filled the null and Zero values with 1.
* Discount_Applied -  The null values in this can be denoted as 0, since it means no discount is applied.
* Purchase_Date - using excel text formula, we can normalize the date fromat.
* Return_status- Using Excel If formula, I converted data into either "Returned" or "Not Returned"
</details>

# Sales Analysis

<img src = "https://github.com/Kriz-Griffin/Retail-Analysis/blob/bee9cab41b9e611d30bf83520fab1c06cd53b792/img/1.png">

* There is a decline in 2025 sales, indicating that the reduce in demand and other issues with the company.
* The average sales did not reach the goal of the average sales of previous years, indicating the decline in performance.
* Electronics (Rural - 129K) dominates in rural store types, but urban sales for electronics are quite low (57K). Groceries (Urban - 118K) is the top performer in urban locations, implying higher footfall or demand in dense urban markets. Stationery performs well in both rural (111K) and suburban areas (101K), indicating balanced demand across regions.
* Product category and Return Status are given as interactive slicing to understand category wise performance.


# Customer Analysis

<img src = "https://github.com/Kriz-Griffin/Retail-Analysis/blob/bee9cab41b9e611d30bf83520fab1c06cd53b792/img/2.png">

* The top 10 locations with highest customer satisfaction is given in this visualization, It can change based on the slicer.
* The average customer satisfaction is 2.7, which is below average since the maximum is 6.
* The Senior Age Group has an average customer satisfaction of 3.14, which is slightly above average. Indicating that they are much more satisfied than other age groups.
* The adult customer generates majority of revenue (approximately 84%), then senior and young people coming behing them respectively.
* In payment preference, Adults prefer all methods fairly equally. For Senior, they prefer wallet and Debit card more than other methods. For younger ones, they prefer wallet and UPI.

# Overall analysis

<img src = "https://github.com/Kriz-Griffin/Retail-Analysis/blob/bee9cab41b9e611d30bf83520fab1c06cd53b792/img/3.png">
