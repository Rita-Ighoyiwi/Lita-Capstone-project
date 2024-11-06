# Lita project
---
This is where i want to document my first grading project, while learning with  Data Analysis with Incubator Hub. 
this particular project show how far you have gone in learning and how much you have particalizes things taught in the class.

## Project 1 Title: Lita Capstone Sales Performance for  a Retail Store

### Project Overview
---
The Data Analysis project aims to analyze the sales performance of a retail store.
were you need to explore Sales data to uncover key insights such as top-selling products, regional performannce, and monthly sales trends. The goal is tp produce an interactive Power BI dashboard that Highlights these findings. 

### Data Sources 
---
The primary source of Data used here is a DataSale.xlsx and this is an open source data that can freely be downloaded from an open source such as Canvas LMS or Gmail account or any other repository site.

### Tools Used
---
- Microsoft Excel
  1. For Data Cleaning
  2. For Analysis
  3. For Data Visualization.
   
- SQL - Structured Query Language for Quering of Data.
- GitHub - for Portfilo Building
- Power Bi -

### Data Cleaning and Preparing
---
in the initail Phase of Data cleaning and preparation, i worked Using Microsoft Excel on the following actions;
1. Data loading and Inspection
2. Formatting and Dta Cleaning
3. Handling missing Variables 

### Data Exploration
---
- Using Pivot Table to perform an initail exploration of the sales data and to summarize the following.
   - Total sales by Product
   - Total sales by Region
   - Total sales by Month

- Use of Excel Formulas to calculate the following metrics.
   - Average Sales per product.
   - Total Revenue By Product.
   - Top-selling products
   - Regional performannce
   - Interactive charts and Slicers
 
 ### Data Analysis
 ---
 This is where I include some basic lines of codes or queries and some DAX expressions were used during the project analysis

 #### Calculating total Sales
 ```Excel
    = SUM(F2 * G2)
 ```

#### Calculating Averages Sales Per Product

```Excel 
 = AVERAGEIFS(H2:H50001, C2:C50001, J6)
```
#### Calculating  Total Revenue by Region

```Excel
   = SUMIFS(H2:H50001, D2:D50001, J16)
```


### Data Visualization
---

#### Tables of Total Sales, Averages sales per product and Total Revenue by Region
---
<img width="872" alt="Table for Total sales, average sales per product and Total Revenue by region" src="https://github.com/user-attachments/assets/07060908-3183-4c7e-ab23-5ea509f65b10">


####  Summerizing the Total Sales by Product, Region and Month using a pivot table
---
<img width="647" alt="Pivot table (Total sales by product, region and month)" src="https://github.com/user-attachments/assets/570b223d-d23f-41ec-8cd4-9e9a1fa15b21">

#### Summarizing the Top Selling products, Regional Performance and Charts
---
This is where i used chart to visualize for insights to bring the performance to life, with the use of slicer to fliter the charts for flexibity.
<img width="170" alt="Capture" src="https://github.com/user-attachments/assets/c7bbed38-91c1-4d23-bb67-c0f46e55af80">
---
<img width="284" alt="Regional performance" src="https://github.com/user-attachments/assets/e12c59ff-4dc2-4235-9f1a-a1ffb644e4e1">
---
<img width="284" alt="Regional performance 2" src="https://github.com/user-attachments/assets/4762d428-1e54-4276-8df7-e3cc97452abf">
<img width="386" alt="Sales data Report chart 1" src="https://github.com/user-attachments/assets/c66d9c31-7fb3-4c58-a280-2b7648c3d0cb">
<img width="534" alt="Sales data Report chart 2" src="https://github.com/user-attachments/assets/904768ca-8e76-4f4f-8ffb-e6be545d07cc">
<img width="378" alt="Sales Data report 3" src="https://github.com/user-attachments/assets/451f3402-6c88-48a0-9aa4-38ddd2d34325">
