# Project-2--Telecom-Customer-Churn-Analysis
•	An analysis of Telecom Customer Churn


**Introduction**

The effect of High value customers churning can affect the growth of the company and also revenue. Gaining insights from the vast amount of data gathered in quarter 2 can help the company identify the key influencers of customer churn and gain more clarity on effective steps to take. This project therefore presents the analysis of the quarter 2 churn rate and proposes next step to help Maven Communications cut down churn risks.


**Problem Statement**

This data set was from Maven analytics monthly challenge for analyst to play around with data and further develop their analytics skills. For this project we were required to assume the position of a Business Intelligence specialist to increase retention and identify High value Customers and churn risks. We were also required to present our findings to the CMO in a single page report.


**Basis**

Since the project is to provide in-depth analysis of how to retain high value customers by cutting risks and also to tell a story we would be covering the following.
•	Identifying the High value customers using their demographics 
•	Use past data to find out the key influencers of customer churning 
•	Identify other possible causes
•	Propose next steps for the CMO using given data


**Data preparation and Exploration**

The data file was downloaded from Maven analytics playground. It came in a CSV format and was imported into power BI. It looked more like this:  

![DATA TELECOM](https://user-images.githubusercontent.com/108904370/179870500-67fad2db-f6b9-4854-8a84-8d69dd96f1ac.PNG)


**Data Cleaning and Transformation**

From Power Bi it was loaded into Power Query for transformation. Cleaning started with the first row made into headers, the columns and rows were checked for irregularities. There were some blank cells and they were filled. The numerical blank rows were filled with zero(0) and the others were filled with “empty cells” to aid analysis.
The dimension tables of Cities and Gender were also created to aid analysis. Here are all the steps taken, fully identified by power query.               
    ![dim for telecom](https://user-images.githubusercontent.com/108904370/179870514-852e0ae1-6892-4233-9632-0daeb9a8406e.PNG)  
 

![telecom project Read me](https://user-images.githubusercontent.com/108904370/179870531-4ddc48a4-8c56-4fb6-8895-710fdb22eae9.PNG)

![telecom project blue](https://user-images.githubusercontent.com/108904370/179870980-1840fdfc-e2c2-4a26-8bd2-bf62ac5b91f1.PNG)

**Analysis and Insights**

•	The High Value customers was determined by the revenue each customer generated for the company. The Female accounted for 6/10 for the top 10 high value customers, and most of them live in San Francisco and most signed up for a 2 years contract.
•	San Diego and Los Angeles had the most customers who churned (185,78) respectively. These customers were mostly between the age range of (60-69) and (70-80). 35.79% who churned were married and 64.21% were single.
•	Work with the Marketing team to create offers like the Offer E that generated high revenue and had less churn rate. These offers should be sent to the customers from time to time.
•	The Month-to-month contract type was less effective, so develop a new contract strategy that would be less tasking for the customers, for instance a 6 month to 1 year contract will perform much better just as much as the 2 years performed well.
•	Engage the Technical team to create better devices that will beat competitors devices to reduce churn rate and retain valuable customers. 
•	Employees should be engaged in trainings yearly, on customer management and support and a quarterly employee performance review should be carried out to keep them on their toes and ensure they are performing efficiently.



