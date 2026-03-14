Sales Performance Analysis

Project Overview

This project analyzes retail sales data from a Superstore dataset in order to identify which products, regions, and customer segments generate the highest revenue and profit. The objective of the analysis is to transform raw transactional data into actionable business insights that can support strategic decision making.

The analysis focuses on discovering patterns in product performance, regional sales behavior, customer segmentation, and profitability drivers. The project demonstrates the complete data analytics workflow from raw data inspection to business recommendations.

Business Problem

Retail companies often generate large sales volumes but struggle with profitability due to excessive discounting, inefficient product portfolios, or regional performance imbalances.

This project investigates the following questions:

Which products generate the highest profit margins

Which regions produce the strongest sales performance

Which customer segments contribute the most revenue

Which products generate high revenue but low or negative profit

The objective is to identify actionable insights that can help management improve profitability and operational efficiency.

Dataset

The dataset used in this project is the Superstore dataset available on Kaggle.

Dataset source:
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

The dataset contains transactional sales records including order details, product categories, geographic regions, customer segments, sales values, profit values, and discounts.

Each row represents a single product within a customer order.

Dataset Description

The analysis is based on the Superstore retail dataset, which contains historical transactional records from a retail business.

The dataset includes information about customer orders, product categories, geographic regions, sales revenue, profit values, and discount levels.

Dataset Characteristics

Number of records: 9,994  
Number of features: 22  

Key Variables

Order Date  
Ship Date  
Region  
Category  
Sub Category  
Customer Segment  
Sales  
Profit  
Discount  

Each record represents a single product within a customer order, allowing detailed analysis of product-level profitability and sales performance.

This dataset is widely used in data analytics training because it reflects common retail business challenges such as discount strategies, product performance differences, and regional market variation.

Tools and Technologies

Python was used as the primary programming language.

The following libraries were used during the analysis:

Pandas for data manipulation and transformation  
Matplotlib for data visualization  
Seaborn for statistical visualizations  
Jupyter Notebook for analysis and documentation  

Project Workflow

Data Understanding

The first stage involved examining the dataset structure. Column names, data types, missing values, and duplicate records were inspected to understand the overall data quality.

Data Cleaning

The dataset was cleaned by verifying column formats, checking inconsistencies, and preparing the data for analysis. Additional time related features were also prepared to support deeper analysis.

Exploratory Data Analysis

Exploratory analysis was performed to identify patterns in sales and profitability. The analysis focused on product categories, sub categories, regions, and customer segments.

Data Visualization

Multiple visualizations were created to clearly communicate patterns in the data. These visualizations illustrate differences in revenue generation, profit margins, and regional performance.

Business Insights

The analysis identified key drivers of profitability as well as areas where the company is losing money due to discounting or product mix.

Key Findings

Technology products generate the highest overall profit.

Copiers are the most profitable sub category despite relatively lower sales volume compared to phones.

Tables generate significant losses due to heavy discounting.

The West region produces the strongest overall sales and profitability.

The Consumer segment contributes the largest portion of revenue.

Strategic Recommendations

Discount levels on furniture products should be controlled to prevent negative profit margins.

High margin products such as copiers and technology products should receive greater promotional focus.

Regional operational strategies should be reviewed in the Central region to improve profit margins.

Customer marketing campaigns should prioritize segments that produce higher margins.

Project Structure

Sales_Performance_Analysis

data  
Contains raw and processed datasets used throughout the analysis

notebooks  
Contains all Jupyter notebooks used in the analytical workflow

reports  
Contains exported charts and visualizations generated during analysis

README.md  
Project documentation and explanation

requirements.txt  
Python dependencies required to run the project

How to Run the Project

Clone the repository to your local machine.

Install the required Python libraries listed in the requirements file.

Open the notebooks in Jupyter Notebook or Visual Studio Code and run them sequentially.





Author

Bilal Shafique

Data Analytics Project