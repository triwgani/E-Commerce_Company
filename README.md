# Analyzing Data with SQL (Structured Query Language) — A Case from an E-Commerce Company

## Introduction
The case study is part#1 of the My Skill Data Analysis Bootcamp Case Project. By examining real-world scenarios, we aim to showcase how SQL empowers businesses to uncover insights, drive informed decision-making, and answering business questions. in this case, an E-Commerce company has been collecting data from its customer during the last 2 years of its operation. The collected data is used to help the management and operation for analyzing and answering some questions they face in their daily business operation. The questions are as follows:

Of all the paid transaction took place during 2021:
1. In what month did the maximum total transaction happen?
2. In what month did the total customer, total order, and the total quantity number of product reach their maximums?

Of all the paid transactions that took place during the 2022:
3. What category of product that drove the maximum value of transaction?

4. By comparing the paid transaction value of each product category between year 2021 and 2022, what are the product categories that experienced improvement, and what are the product categories that experienced decrement of their corresponding transaction values during the period of 2021 and 2022?
5. Display the top 10 sku_name (along with its corresponding category) based on the paid transaction value during the 2022. as well as the total number of customer, total_order, and total quantity!
6. Display the top 5 of the mostly used payment method in 2022 for all paid transactions!
7. Sort the following 5 products based on their corresponding paid transaction value: (Samsung, Apple, Sony, Huawei, and Lenovo)!
8. As per question no 3, provided that the profit is determined by the following formula (profit = after_discount — (cogs x ordered quantity), make a profit comparison between year 2021 and 2022 for each paid product category prior to displaying the percentage (%) of the profit disparity between 2021 and 2022!
9. Provided the result in no 8, display the top 5 of SKU with the highest contribution in year 2022, based on the product category with the highest profit grow between 2021 and 2022!
10. Display the number of unique order that use the top 5 payment methods (from no 6) based on the product category in year 2022!

## Datasets
There are 4 datasets used in analyzing and answering the above questions, mainly the order_detail, sku_detail, customer_detail, and payment_detail datasets. They are modified data and were retrieved from an e-commerce company system which enables it to collect the transactions from their customers making the purchases for the last 2 years (2021 and 2022). Source: [https://www.kaggle.com/datasets/zusmani/pakistans-largest-ecommerce-dataset](https://www.kaggle.com/datasets/zusmani/pakistans-largest-ecommerce-dataset)
