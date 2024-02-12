# Customer Incident Resolution Report


![Power BI](https://img.shields.io/badge/Analytics-Power_BI-yellow?logo=powerbi&logoColor=white&style=flat-square) <br>
![SQLite](https://img.shields.io/badge/Database-SQLite-blue?logo=sqlite&logoColor=white&style=flat-square) <br>
![Python](https://img.shields.io/badge/Programming-Python-blue?logo=python&logoColor=white&style=flat-square) <br>



<hr style="border: 2px solid gray;">

### Project Objective
---

This Power BI report tracks technical issues and error messages encountered by customers on our online store. It categorizes incidents, determining whether they require attention from our internal IT team or need to be escalated to the courier responsible for deliveries. Additionally, the report monitors resolved incidents, providing insights into their resolution and turnaround time. Its purpose is to ensure that customer inquiries regarding online purchases are promptly addressed, promoting customer satisfaction.


### Dataset Information
---

The dataset simulates real data gathered from an online shopping website. It was extracted from the online application and stored in a SQLite database before being analyzed using Power BI.

### Project Approach
---

To achieve the project objective, the following ETL and Power BI report development steps were followed....

**1. Data Extraction:**
The data was exported from the admin version of the online store application in Excel format. A python script was created to create a table to host the initial fact data and the associated dimension data in a SQLite database.

**2. Data Transformation:**
In SQLite, views are crafted to extract specifically needed data for reporting purposes. These views are then imported into Power BI Power Query to undergo data transformation, ensuring its readiness for analysis.

**3. Power BI report development:**
Data modeling is done in Power BI and a reprot is developed, with the key indicators for open and resolved incidents, including assignees and some requested details about each case.


### The Resultant Power BI report
---

<p align="center">
  <img src="https://github.com/CarolMmai/Customer-Incident-Resolution-Report/blob/main/Customer%20Incident%20Resolution%20Report.gif" width="800" height="450" alt="Customer Incident Resolution Report">
</p>


### Value added to the business
---

1. Quicker customer technical and delivery query resolution
2. Ability to delegate query tasks better 
3. Avoiding losing clients and probability of logging product returns
4. Overall increase in profits
