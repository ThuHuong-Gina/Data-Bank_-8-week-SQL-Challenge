![image](https://github.com/ThuHuong-Gina/Data-Bank_8-week-SQL-Challenge/assets/141025228/e7b3aebf-c916-4614-8b52-8e59fb1f3313)
Please check the challenge here: [Data Bank](http://https://8weeksqlchallenge.com/case-study-4/)


# **1. Introduction**

There is a new innovation in the financial industry called Neo-Banks: new aged digital only banks without physical branches.

Danny thought that there should be some sort of intersection between these new age banks, cryptocurrency and the data world…so he decides to launch a new initiative - Data Bank!

Data Bank runs just like any other digital bank - but it isn’t only for banking activities, they also have the world’s most secure distributed data storage platform!

Customers are allocated cloud data storage limits which are directly linked to how much money they have in their accounts. There are a few interesting caveats that go with this business model, and this is where the Data Bank team needs your help!

The management team at Data Bank wants to increase their total customer base - but also needs some help tracking just how much data storage their customers will need.

This case study is all about calculating metrics, growth, and helping the business analyze their data in a smart way to better forecast and plan for their future developments!

* Available Data
The Data Bank team have prepared a data model for this case study as well as a few example rows from the complete dataset below to get you familiar with their tables.

---------**Entity Relationship Diagram**----------
![image](https://github.com/ThuHuong-Gina/Data-Bank_-8-week-SQL-Challenge/assets/141025228/e555a140-8874-4ff9-a5f7-ffd974f11bd2)

# **2.Insights**
## Customer Nodes Exploration
- There are 5 nodes (or branches) in the data bank system
- 3 regions have the most branches are Australia, America, and Eurore. There are also the highest numbers of customers allocated respectively.
- On average, It takes  14 days for customers to be alocated
## Customer Transaction
### 1. What is the unique count and total amount for each transaction type?
![image](https://github.com/ThuHuong-Gina/Data-Bank_8-week-SQL-Challenge/assets/141025228/986e99c8-9bdb-46bd-a9fa-debdfa2237a8)
### 2. What is the average total historical deposit counts and amounts for all customers?
![image](https://github.com/ThuHuong-Gina/Data-Bank_8-week-SQL-Challenge/assets/141025228/41a38ac1-457b-4921-8bc9-69d30e42890a)
### 3. For each month — how many Data Bank customers make more than 1 deposit and either one purchase or withdrawal in a single month?
![image](https://github.com/ThuHuong-Gina/Data-Bank_8-week-SQL-Challenge/assets/141025228/46a078c3-7891-4da2-84b7-7677072233b7)
### 4. What is the closing balance for each customer at the end of the month?
![image](https://github.com/ThuHuong-Gina/Data-Bank_8-week-SQL-Challenge/assets/141025228/e79e2ad1-1285-4451-9de6-520723697cc7)
### 5. What is the percentage of customers who increase their closing balance by more than 5%?
![image](https://github.com/ThuHuong-Gina/Data-Bank_8-week-SQL-Challenge/assets/141025228/47c39a3d-dd80-4a6b-a39b-dcd28c8afc73)

## C. Data Allocation Challenge
### 1. running a customer balance column that includes the impact of each transaction
(Running balance is the sum of present debit and credit amounts after the previous day's balance have been deducted. Running balance is used to manage individual accounts in a business.)
![image](https://github.com/ThuHuong-Gina/Data-Bank_8-week-SQL-Challenge/assets/141025228/7cf5cd6c-2fba-4eac-a532-1be9bb712fe2)
### 2. Customer balance at the end of each month
![image](https://github.com/ThuHuong-Gina/Data-Bank_8-week-SQL-Challenge/assets/141025228/3fe69dea-0bfa-41ca-9c8d-04478ae08bcc)
### 3. minimum, average, and maximum values of the running balance for each customer
![image](https://github.com/ThuHuong-Gina/Data-Bank_8-week-SQL-Challenge/assets/141025228/6a8cbbe5-2b01-48f3-9a5b-5c3e8b226cde)

To test out a few different hypotheses - the Data Bank team wants to run an experiment where different groups of customers would be allocated data using 3 different options:

Option 1: data is allocated based off the amount of money at the end of the previous month
Option 2: data is allocated on the average amount of money kept in the account in the previous 30 days
Option 3: data is updated real-time

** So lution for each option in the code file**

