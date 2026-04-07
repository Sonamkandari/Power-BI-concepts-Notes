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

# How to Review Data and Perform Data Transformation

## Using DAX Query

- In some cases, a column may contain null values or blank spaces.
- These can be handled using DAX expressions to replace or manage missing values.

---

<img width="70" height="208" alt="DAX Query View" src="https://github.com/user-attachments/assets/b2dd0366-8e99-4c5f-8fd1-6f50fbee775e" />

---

<img width="672" height="389" alt="DAX Example" src="https://github.com/user-attachments/assets/b9087ff0-c07c-4368-b147-a53e6801aa20" />

---

<img width="802" height="120" alt="DAX Formula Bar" src="https://github.com/user-attachments/assets/8b681cc7-2a74-49f7-a04d-b79fd2b65d69" />

---

- DAX (Data Analysis Expressions) is the formula language in Power BI used to create calculations and apply custom logic to your data model.

---

## Power Query (Data Transformation Tool)

- Power Query is used to clean, transform, and prepare data before loading it into the data model.
- It is the preferred tool for handling missing values, changing data types, and shaping data.

---

<img width="893" height="423" alt="Power Query Editor" src="https://github.com/user-attachments/assets/64b9e5c6-cc09-45cb-ad73-6ffe887d6fc8" />

---

## DAX vs Power Query

- **DAX**
  - Used after data is loaded into the model  
  - Creates new columns or measures  
  - Stores the result of calculations  

- **Power Query**
  - Used before data is loaded  
  - Performs data cleaning and transformation  
  - Does not store unnecessary intermediate results  

---

## Report View (Data Visualization)

### Canvas Overview

- The report canvas is where visualizations are created.
- Right-side panel includes:
  - Filters  
  - Visualizations  
  - Data (Fields)  

---

<img width="400" height="384" alt="Report Canvas" src="https://github.com/user-attachments/assets/0f34fe8d-6827-42c0-9fdf-37eb43d63e51" />

---

## Building Visuals

- Most visuals require:
  - **Dimensions** (categorical data)  
  - **Measures** (numerical values)  

---

## First Bar Chart

---

<img width="505" height="393" alt="Bar Chart Example 1" src="https://github.com/user-attachments/assets/0af77f00-8870-4cbe-957e-bf627627884d" />

---

<img width="888" height="650" alt="Bar Chart Example 2" src="https://github.com/user-attachments/assets/ec8e183d-3068-4d97-84b9-4927174c6421" />

---

## Slicer

- A slicer is an interactive filter used in reports.
- It allows users to dynamically filter data in visuals.

---

<img width="1155" height="715" alt="Slicer Example" src="https://github.com/user-attachments/assets/e0d23227-7b7b-4f40-873b-dc3d2b8d6f9a" />

---

<img width="1132" height="640" alt="Slicer Example 2" src="https://github.com/user-attachments/assets/a3a25b7b-68bf-459b-b636-c23f5e77496c" />

---

## Publishing the Dashboard on Power BI Service

- After creating reports, you can publish them to Power BI Service.
- This allows sharing dashboards with others and accessing them online.

---

<img width="870" height="506" alt="Publish Dashboard" src="https://github.com/user-attachments/assets/eb0f7990-2aaa-4491-9025-1d68441fb796" />




