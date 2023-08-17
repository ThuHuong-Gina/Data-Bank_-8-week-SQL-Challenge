![image](https://github.com/ThuHuong-Gina/Data-Bank_8-week-SQL-Challenge/assets/141025228/b46fb9dc-fc5f-4902-87c9-5315fedda617)


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

# ** DataBank Structure **
 A financial technology company that helps its consumers with transactional banking services in a novel, more convenient way. 

* DataBank offers banking services like: 
 - Deposits
 - Withdrawals
 - Purchases
* DataBank operas in 5 regions: Australia, America, Africa, Asia, Europe
- There are 5 nodes (or branches) in the data bank system
- 3 regions have the most branches are Australia, America, and Eurore. There are also the highest numbers of customers allocated respectively.
- On average, It takes  14 days for customers to be alocated
- Median, 80th and 95th oercentile for this same reallocation days metric for each region
  ![image](https://github.com/ThuHuong-Gina/Data-Bank_8-week-SQL-Challenge/assets/141025228/c951ab52-309d-4e61-b245-3ee3a0a280d4)

* Sercurity
  - DataBank operates on a global network of nodes for secure customer infomation distribution.
  - Customer data and funds are frequently updated and distrubuted to reduce risk like online haking digital identity risks.
  - Customer allocated is random based on region for an extra layer of security.
  - DataBank continuously impoves and refines protocols based on reallocated metrics.

### Data Allocation
In order to expand its customer base, DataBank tested hypotheses and experimented with allocating data to differenr customer groups using 3 options:
  
  - Option 1: data is allocated based off the amount of money at the end of the previous month
  - Option 2: data is allocated on the average amount of money kept in the account in the previous 30 days
  - Option 3: data is updated real-time
    
_ _ Question: How much data would have been required for each option on a monthly basis _ _ 
Option 1:
![image](https://github.com/ThuHuong-Gina/Data-Bank_8-week-SQL-Challenge/assets/141025228/2ba1c1ea-671d-4809-a897-4fee057b076e)
--> Insight: 
  * There are more deposits than withdrawals and purchases  in all the months which led to lower or negative customer balances   

  * DataBank can leverage this information to identify customer behavious and usage patterns, such as identifying customers who consistently have high data storage needs and target them with promotional offers and special servicea.

Option 2:
![image](https://github.com/ThuHuong-Gina/Data-Bank_8-week-SQL-Challenge/assets/141025228/fe600bcb-b976-450a-ab47-863c0a96294c)

  * There are more withdrawsl and purchases than deposits in all the months which led to lower or negative customer balances which led to lower customer's balances
  * Using this approach may not be suffient becasue the avearage balance over the previous 30 days is decreasing over time
  * Databank should consider re-evalute their allocation straegy for these cusomers orconsider providing additional data allowances to preventnegative customer experiences.

Option 3: 
![image](https://github.com/ThuHuong-Gina/Data-Bank_8-week-SQL-Challenge/assets/141025228/aa1bdcbe-e508-4680-9f4c-617628e70f6b)

  * Almost the same as option 2
  *  In terms of the allocation of data to customers, this uutput suggest that more data may be required for the first 2 months of the year.

# Conclusion
DataBank offers the most advantage security systerm making it more safe for customers and enhances swift and secure transactions.

It can also carry out more tested hypotheses to increase customer base and in order to understand customer's behavious, needs and expectation.
