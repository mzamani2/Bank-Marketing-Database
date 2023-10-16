# Bank Marketing Data Management Project

This project involves managing and analyzing data collected from a recent marketing campaign conducted by a bank. The goal is to clean, reformat, and store the data in a way that allows easy handling of future marketing campaigns. Additionally, the project requires creating a PostgreSQL database and writing SQL scripts to initialize and populate the necessary tables.

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Database Design](#database-design)
- [Getting Started](#getting-started)
- [Usage](#usage)

## Introduction
Personal loans are a significant revenue stream for banks, and understanding customer behavior through marketing campaigns is crucial. This project focuses on organizing and managing the data collected from a recent marketing campaign to optimize future campaigns.

## Project Overview
The project involves:
1. **Data Preparation and Cleaning:**
   - The provided CSV file, "bank_marketing.csv," is cleaned, reformatted, and split into separate files based on the required tables using the Pandas library.
  
2. **Database Setup:**
   - Designing and creating a PostgreSQL database to store campaign data efficiently.
  
3. **SQL Scripting:**
   - Writing SQL scripts to create the required tables (`client`, `campaign`, `economics`) and populate them with data from the CSV files.

## Database Design
The database comprises three main tables:
1. **client:**
   - Contains client information such as age, job, marital status, education, credit status, housing loan status, and personal loan status.

2. **campaign:**
   - Stores campaign-related data including campaign and client IDs, contact details, and campaign outcomes.

3. **economics:**
   - Contains economic indicators associated with each client, such as employment variation rate, consumer price index, euribor rate, and number of employees.

## Getting Started
1. Clone this repository to your local machine.
2. Ensure you have PostgreSQL installed.
3. Follow the usage instructions to set up the database and populate it with data.

## Usage
1. **Data Cleaning and Preparation:**
   - Use the provided Python script to clean and split the data based on the specified tables.
   
2. **Database Initialization:**
   - Execute the SQL scripts provided in the project to create the necessary tables and set up the database schema.

3. **Populating the Database:**
   - Use the SQL `COPY` commands to import the cleaned data into the respective tables.

For detailed steps and commands, refer to the project documentation and scripts.

This project aims to facilitate efficient data management and analysis for future marketing campaigns, ultimately assisting the bank in making informed business decisions.
