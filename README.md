# Cellphones Information Analysis
## Objective
The goal of this repository is to analyze cellphone sales transactions and derive actionable insights based on a predefined schema. The database, “Cellphones Information,” encompasses details about cellphone manufacturers, models, customers, locations, and transactional data.
## Overview
This repository provides SQL queries to answer specific business questions related to cellphone sales, customer behavior, and product performance. The dataset is assumed to have the following schema:
## Datasets
- Dim_Manufacturer: Contains manufacturer details.
- Dim_Model: Contains model details.
- Dim_Customer: Contains customer details.
- Dim_Location: Contains location details.
- Fact_Transactions: Stores sales transaction data.
## Database Schema
![Screenshot 2024-12-12 015544](https://github.com/user-attachments/assets/9a0a2da7-6efa-4cb0-a337-b96377f3ef47)

## Process
The repository provides the following steps to manage and analyze the data:
- Use SQL CREATE DATABASE statement to initialize the database.
- Define the schema using SQL CREATE TABLE statements with appropriate data types for each column.
- Ensure referential integrity by defining primary and foreign keys for relationships between tables.
- Populate the tables with sample or real data using INSERT INTO statements.
## Database Creation:
- <a href="https://github.com/SourabhaSekharRout/Cellphones-Information-Analysis/blob/main/Create%20Database%20and%20Tables.sql">Database & Tables</a>
## Business Queries
The repository provides SQL queries to answer the following business questions:
- List all the states in which customers have bought cellphones from 2005 till today.
- Identify the US state buying the most 'Samsung' cellphones.
- Show the number of transactions for each model per zip code per state.
- Find the cheapest cellphone along with its price.
- Calculate the average price for each model in the top 5 manufacturers by sales quantity, ordered by average price.
- List customers and their average spending in 2009 where the average is higher than $500.
- Identify models that were in the top 5 by quantity for 2008, 2009, and 2010.
- Determine the manufacturer with the second-highest sales in 2009 and 2010.
- Find manufacturers who sold cellphones in 2010 but not in 2009.
- Analyze the top 100 customers by their average spending, quantity per year, and percentage change in spending.
## Analysis:
- <a href="https://github.com/SourabhaSekharRout/Cellphones-Information-Analysis/blob/main/Cellphones%20Information%20Analysis.sql">Business Analysis</a>
## Features
- Analyze cellphone sales data effectively.
- Gain insights into customer and manufacturer performance.
- Adaptable schema for various business scenarios.
