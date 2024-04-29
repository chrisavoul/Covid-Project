# COVID-19 Data Exploration Project

## Overview

This project involves exploring COVID-19 data using SQL queries in Jupyter notebooks. The queries utilize various SQL functionalities such as joins, common table expressions (CTEs), temporary tables, window functions, aggregate functions, and creating views. The aim is to analyze COVID-19 statistics and trends across different regions and time periods.

## Skills Used

- Joins
- Common Table Expressions (CTEs)
- Temporary Tables
- Window Functions
- Aggregate Functions
- Creating Views
- Converting Data Types

## Queries

Below are some of the SQL queries used in this project:

- **Selecting Data**: Retrieve COVID-19 data from the database, filtering out records where the continent is not specified.
- **Total Cases vs Total Deaths**: Calculate the likelihood of dying if contracting COVID-19 in a specific country.
- **Total Cases vs Population**: Determine the percentage of the population infected with COVID-19 in different countries.
- **Countries with Highest Infection Rate**: Identify countries with the highest infection rates compared to their population.
- **Countries with Highest Death Count**: Find countries with the highest death counts per population.
- **Breaking Things Down by Continent**: Analyze continents with the highest death counts per population.
- **Global Numbers**: Calculate global COVID-19 statistics such as total cases, total deaths, and death percentages.
- **Total Population vs Vaccinations**: Explore the percentage of the population that has received at least one COVID-19 vaccine dose.
- **Using CTEs and Temporary Tables**: Utilize common table expressions (CTEs) and temporary tables to perform calculations on partitioned data.
- **Creating View**: Create a view to store data for later visualizations.

## Usage

1. Ensure you have access to the necessary COVID-19 datasets in your database.
2. Open the provided Jupyter notebooks containing the SQL queries.
3. Execute the queries in the notebooks to analyze the COVID-19 data and explore the trends.

## Dashboard Screenshot
![Covid Global Dashboard](https://github.com/chrisavoul/Covid-Project/blob/main/Screenshot%202024-04-29%20195645.png?raw=true)

The dashboard provides a comprehensive visualization of COVID-19 data through four distinct sheets:

1. **Global COVID-19 Statistics**: This sheet presents a table detailing the global number of COVID-19 cases, deaths, and the corresponding death percentage.

2. **Death Counts by Continent**: A bar chart illustrates the distribution of death counts per continent, offering insights into regional variations.

3. **Infection Percentage by Country**: The filled map visually represents each country's percentage of infection, allowing for a quick understanding of the spread across different regions.

4. **Chronological Infection Trends**: This dynamic visualization traces the average number of infections over time in select countries including the United States, United Kingdom, Mexico, China, India, and Greece, providing insights into the progression of the pandemic.

The dashboard offers a comprehensive overview of COVID-19 trends, facilitating informed decision-making and analysis.
