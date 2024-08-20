# Global Superstore Analytics

## Table of Contents

- [Problem Statement and Overall Objectives](#problem-statement-and-overall-objectives)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning - Power Query Editor (DAX)](#data-cleaning---power-query-editor-(dax))
- [Exploratory Data Analysis](#exploratoty-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#resultsfindings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

### Problem Statement and Overall Objectives

The main purpose of this Global Superstore project was/is to investigate the company's sales and profit by analyzing the historical dataset and tracking 
the sales and profit for each year, segment, and market. Additionally, it highlights the impact of different customers and products within the company's business. 

Data Scope: The data scope for this analysis will include all the years during which the company has sold products and managed orders.
View Required: A summary page presenting the company's sales and profit, taking into consideration the different factors mentioned above.

### Data Sources 

The data used for this analysis includes the orders, people, and returns data, which are stored in an XLSX format across different sheets. 
The data has been uploaded to Power BI as an Excel workbook.

### Tools

- Microsoft Power BI: The tool is used to create comprehensive, interactive data visualizations and share important business insights. 
      [Learn more](https://www.microsoft.com/sv-se/power-platform/products/power-bi?ef_id=_k_cb76b16ddc2510de7ad4d7779827f495_k_&OCID=AIDcmmc1fckbp7_SEM__k_cb76b16ddc2510de7ad4d7779827f495_k_&msclkid=cb76b16ddc2510de7ad4d7779827f495&market=se)

### Data Cleaning - Power Query Editor (DAX)

Initially the following tasks were performed: 

1. Data collection and inspection
   Since there are multiple sheets in the data file, a critical quality check was performed before collecting the data,
   such as verifying column count and headers, to ensure that the data is correct and ready for uploading.
   
2. Transformation & Modeling
   In Power Query Editor, some critical tasks were performed to transform the dataset and make it more suitable for analysis based on the project's goals.
   For example, the data type was changed for some columns, and new columns were created—both custom and conditional—to extract needed information,
   such as order years and delivery days.

   NB! Since the tranformation & modeling phase is iterative, this step was performed several times when different changes were needed to correct the dataset.

   Once the tranformed data was uploaded, in the modeling view, the desired model/relationship was created between the different tables/data.

### Exploratory Data Analysis

EDA involved exploring the Global Superstore data to answer key questions, such as: 

- What are the total sales, and which years had the highest and lowest performance?
- How many products were sold overall, and how does this break down by year, segment, and market?
- What is the average delivery time for order shipments?
- How many orders have been returned over the years?
- Which are the top 6 most profitable and least profitable products in sales?
- Who are the company's top 10 customers, and which segment includes most of them?

### Data Analysis

#### Summary Page
The dashboard shows information about profit and sales based on different factors, such as segment, market, and year. 
It also displays the top customers, as well as profit and loss products. 
Finally, the global map shows sales by region, which facilitates comparison with sales by market.

<img width="1002" alt="Image_DashB_PO" src="https://github.com/user-attachments/assets/0bd89925-ebda-4cac-8738-b5b83de733a7">

### Results/Findings





















