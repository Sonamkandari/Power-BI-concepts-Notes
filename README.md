# Power BI Concept Notes

## Power BI Desktop

Power BI Desktop is a business intelligence and data visualization tool developed by Microsoft. After downloading and installing Power BI Desktop, the first step is to understand how to navigate through its interface.

---

## Types of Views in Power BI

Power BI provides multiple views to work with data effectively:

### 1. Report View
- The main view used for creating visualizations.
- Used to design dashboards with charts, graphs, and filters.
- Helps present insights in an interactive format.

---

### 2. Table View (Data View)
- Displays raw data in tabular format.
- Helps verify whether the data is loaded correctly.
- Allows switching between tables from the right-side panel.

---

### 3. Model View
- Used for data modeling.
- Allows creation of relationships between tables.
- Helps organize data into a structured format.

---

## Advanced Views (Advanced Topics)

- DAX Query View  
- TMDL View (Tabular Model Definition Language)

These views are used for advanced data modeling and querying.

---

## Step 1: Connecting Data in Power BI

Before building reports, connect your data sources.

---

## Power BI Ribbon (Main Toolbar)

The ribbon includes the following options:

- Get Data  
- Excel Workbook  
- Power BI Datasets / Catalog  
- SQL Server  
- Enter Data  
- Dataflows  
- Recent Sources  

---

<img width="425" height="103" alt="Power BI Ribbon" src="https://github.com/user-attachments/assets/0eeb38eb-9d7d-4ac4-bfa6-777bc70a4c42" />

---

## Selecting Data Sources from Model View

Go to the Model View and select the common data sources.

---

<img width="201" height="413" alt="Model View Data Sources" src="https://github.com/user-attachments/assets/c6e53be0-9123-40da-9e0e-cdb42cd8d841" />

---

## Getting Data from CSV Files

Steps:
1. Click on **Get Data → Text/CSV**  
2. Select your CSV file  
3. Preview the data  
4. Click **Load**  

---

<img width="398" height="255" alt="Import CSV" src="https://github.com/user-attachments/assets/5c38d4c9-e8ae-49fb-8eed-3379b738123b" />

---

## Connected Data (Files)

- Loaded Customer CSV file  
- Loaded Orders CSV file  

Both datasets are available in:
- Table View  
- Model View  

---

## Model View (Data Modeling)

- Used to build the data model  
- Create relationships between tables  
- Define keys and organize data efficiently  

---

<img width="802" height="411" alt="Model View" src="https://github.com/user-attachments/assets/5f38aba8-acfd-4353-925f-49f4f59508ba" />

---

## Table View (Inspect Data)

- Displays data in a table format  
- Helps ensure data is correctly loaded  
- Allows switching between tables using the right panel  

---

<img width="782" height="411" alt="Table View" src="https://github.com/user-attachments/assets/361d6a03-451c-4862-8a81-3974d26c4640" />

---

## Switching Between Tables

You can switch between tables from the right-side panel by clicking on the table name.

---

<img width="1893" height="794" alt="Switch Tables" src="https://github.com/user-attachments/assets/16afd400-cdfe-45c5-bb15-67cade586bd8" />

---

## Data Transformation and Cleanup

Data cleaning is an important step before analysis.

### Example

In the Orders table, the `Order_Date` column may not be in the correct format.

### Steps to Fix

1. Select the `Order_Date` column  
2. Go to **Column Tools**  
3. Change the data type to **Date**  
4. Apply changes  

---

## Summary

- Power BI has three main views: Report, Table, and Model  
- Data can be imported from multiple sources such as CSV, Excel, and SQL Server  
- Model View is used for managing relationships  
- Table View is used for inspecting data  
- Data transformation ensures clean and accurate analysis  
