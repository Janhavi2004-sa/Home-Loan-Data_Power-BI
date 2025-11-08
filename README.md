# Analyzing-Home-Loan-Data_Power-BI
<img width="823" height="655" alt="image" src="https://github.com/user-attachments/assets/d5a90e3d-c219-46cb-9510-5b646a2c4ffc" />



**1. Data Model Setup**

All sheets from Home_Loan_Data.xlsx were imported into Power BI. 

Relationships were created as follows: 

1.	Customer→ Products via ProductID 
2.	Customer → Channel Via ChannelID
3.	Customer → Sanction Data via Customer Number
4.	Customer → Branch via Branch Code
5.	Customer → Recovery Data via Customer Number
   
The model diagram shows a star schema connecting fact and dimension tables.

________________________________________

**2. Data Cleaning**

Using Power Query Editor: 

•	Replaced blank Regions with “Unknown”. 

•	Removed duplicate rows from Customers table.

•	Data modelling using power BI relationships.

•	Geographical map using Power BI map visualization.

•	Dax calculation : sum, count, average.

________________________________________

**3.Multivariate Analysis**

1.	Funnel chart to compare applied, sanctioned, disbursed and recovered amount.
2.	Applied loan amount analysis based on customer features(Age, salary, gender, occupation, type of customer) – AI features.

________________________________________

**4. Dashboard Layout**

A single dashboard page was designed with clear visuals:

1.	KPI Cards: Total Customer, Total Loan Applied, Total Sanctioned Amount, Total Disbursed Amount, Total Recovered Amount.
2.	Branch wise loan applied (Map)
3.	Product wise loan applies (bar chart)
4.	Channel wise loan applied ( Donut chart)
5.	Loan application trend (Line chart)
   
This layout presents business performance at a glance.

________________________________________

**5. Slicer Interaction**

Added interactive Slicers for Gender, and Branch Name: 

•	Gender→ Customers[Gender] 

•	Branch Name→ Branch Data[Branch Name] 

All visuals update dynamically when filters are applied, enhancing user interaction.

________________________________________
