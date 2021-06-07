# Sales-Management-Project
## Business Request
The business request for this data analyst project was an executive sales report for sales managers. Based on the request that was made from the business following user stories were defined to fulfill delivery and ensure that acceptance criteria’s were maintained throughout the project.

![image](https://user-images.githubusercontent.com/83585688/120995198-ccd3e400-c7a2-11eb-82ba-6f228902a527.png)


## Data Cleansing & Transformation (SQL)
To create the necessary data model for doing analysis and fulfilling the business needs defined in the business request the following tables were extracted using SQL.
One data source (sales budgets) were provided in Excel format and were connected in the data model in a later step of the process.

Below are the SQL statements for cleansing and transforming necessary data.

### • Cleaning and Extracing data from DIM_Date using SQL Queries.
<img width="955" alt="SQL" src="https://user-images.githubusercontent.com/83585688/120993511-3652f300-c7a1-11eb-9760-fa1adc66f138.png">


### • Cleaning and Extracing data from DIM_Product using SQL Queries.
<img width="575" alt="SQL DIM Products" src="https://user-images.githubusercontent.com/83585688/120993522-38b54d00-c7a1-11eb-865d-b86caa8bbcd6.png">


### • Cleaning and Extracing data from DIM_Internet_Sale using SQL Queries.
<img width="649" alt="SQL DIM Internet Sales" src="https://user-images.githubusercontent.com/83585688/120993527-3a7f1080-c7a1-11eb-8057-c76900f7880b.png">


### • Cleaning and Extracing data from DIM_Calendar using SQL Queries.
<img width="638" alt="SQL DIM Cal" src="https://user-images.githubusercontent.com/83585688/120993536-3c48d400-c7a1-11eb-8e0d-d2efaa407700.png">

## Data Model
Below is a screenshot of the data model after cleansed and prepared tables were read into Power BI.
This data model also shows how FACT_Budget has been connected to FACT_InternetSales and other necessary DIM tables.

<img width="698" alt="Power BI relationship" src="https://user-images.githubusercontent.com/83585688/120957619-a2b6fd80-c773-11eb-94e1-a76e2a2ce549.png">

## Sales Management Dashboard
The finished sales management dashboard first page works as a dashboard and overview, other two pages focused on combining tables for necessary details and visualizations to show sales over time, per customers and per products.

- ### Sales Overview Dashoard
<img width="721" alt="Power BI" src="https://user-images.githubusercontent.com/83585688/120957932-34266f80-c774-11eb-85e4-328760cc26ab.png">


- ### Customer Details Dashoard
<img width="723" alt="Power BI2" src="https://user-images.githubusercontent.com/83585688/120957933-37b9f680-c774-11eb-879a-600c81346592.png">


- ### Product Details Dashoard
<img width="737" alt="Product Details" src="https://user-images.githubusercontent.com/83585688/120994778-723a8800-c7a2-11eb-8c94-e92fe04e803e.png">

## Project Sample
![0cc43fe49c864d29165de56fbb07d9ce54f41ee6](https://user-images.githubusercontent.com/83585688/120959107-b1eb7a80-c776-11eb-82ca-69b0c54436aa.gif)


This was a personal project based on fictional company and sample dataset.
