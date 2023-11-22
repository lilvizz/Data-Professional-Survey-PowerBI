# Data Professional Survey Power BI Project

## Overview

This repository contains a Power BI project that analyzes survey data from data professionals, including data engineers, focusing on aspects such as salary, work/life balance, and more. The project involves data preparation in Excel, storage and retrieval in SQL Server Management Studio (SSMS), and visualization using Power BI. Additionally, Data Analysis Expressions (DAX) have been employed for advanced analytics.

## Prerequisites

Before getting started, ensure that you have the following software installed:

- **Microsoft Excel:** Used for data preparation and initial analysis.
- **SQL Server Management Studio (SSMS):** Required for managing and querying the SQL database.
- **SQL Server (or SQL Express):** The database engine where survey data will be stored.
- **Power BI Desktop:** Used for creating and modifying Power BI reports.
- **DAX Editor (optional):** For more advanced DAX formula editing in external editors.

## Setup Instructions

### 1. Excel Data Preparation

1. Open the Excel file (`SurveyData.xlsx`) in the 'Data' folder.
2. Review and clean the data as needed.
3. Save the Excel file with the prepared survey data.

### 2. SQL Server Database Setup

1. Open SSMS and connect to your SQL Server instance.
2. Run the SQL scripts in the 'SQL Scripts' folder:
   - `CreateDatabase.sql`: Creates the database for survey data.
   - `CreateTables.sql`: Defines tables for survey responses.
   - `InsertData.sql`: Inserts data from the Excel file into the tables.

### 3. Power BI Report Creation

1. Open Power BI Desktop.
2. Connect to the SQL Server database using the 'Get Data' option.
3. Load relevant tables into Power BI.
4. Design visualizations and reports based on survey analysis requirements.
5. Utilize DAX for advanced calculations and analytics.
6. Save the Power BI file (`SurveyAnalysis.pbix`) in the 'Power BI' folder.

## Folder Structure

- **Data:** Contains the Excel file with raw survey data.
- **SQL Scripts:** Includes SQL scripts for database and table creation.
- **Power BI:** Holds the Power BI file with visualizations, reports, and DAX formulas.

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests. Your feedback and enhancements are highly appreciated.


