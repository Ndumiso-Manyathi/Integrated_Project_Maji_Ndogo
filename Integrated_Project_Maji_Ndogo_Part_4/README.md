# Actionable Insights: Empowering Decisions

## Overview:
Our focus now is transforming raw data into actionable insights to facilitate informed decision-making. This phase involves shaping the data into meaningful views, providing crucial information for decision-makers and engineers tasked with solving the water crisis in Maji Ndogo.

## Focused Query Analysis: Targeted Insights
This section aims to conduct specific analysis on the data by formulating focused queries to address key questions. It emphasizes efficient data usage by targeting the necessary information from relevant tables.

## Schema Overview:
### Available Tables:
- employee
- global_water_access
- location
- visits
- water_quality
- water_source
- well_pollution
- Auditor_report


### Analytical Approach:
The approach involves joining tables to establish relationships between provinces, towns, water sources, population served, queue times, and pollution data. Specifically, the focus is on identifying relationships that reveal insights such as:

1. Distribution of water sources across provinces and towns.
2. Identifying towns with prevalent tap issues.
3. Analyzing queues and pollution levels in specific regions.

### Constructing the Project_progress Table:
This section emphasizes the need to assemble data into a comprehensive table to facilitate easier analysis. It outlines the process of joining relevant tables to form the basis of future analysis.


## Summary Report and Insights:
A summary of crucial insights extracted from previous analyses, including key statistics and identified challenges in Maji Ndogo's water crisis.

## Plan of Action:
A detailed plan outlining actionable steps derived from the insights, including prioritized solutions and practical approaches to address water source issues. The plan involves short-term and long-term solutions targeting shared taps, wells, infrastructure, and rural areas.

### Practical Solutions:
Outlined steps to implement practical solutions such as dispatching trucks to regions using rivers, installing filters for wells, optimizing shared tap access, and addressing broken infrastructure.

### Final Goal: Implementing the Plan in the Database:
A clear outline of the final objective - implementing the plan into the database. This involves creating the 'Project_progress' table, detailing necessary information for the engineering teams to execute repairs, upgrades, and maintenance. Key attributes include addresses, water source types, repair status, completion dates, and upgrade details.

## Instructions for Use:
### Guidelines for Contributors and Users:
- Instructions for setting up the project environment and database.
- Guidance on executing SQL queries, understanding dataset nuances, and contributing to the project.

## Answered Queries:

### 1. How many UV filters do we have to install in total?

### 2. If you were to modify the query to include the percentage of people served by only dirty wells as a water source, which part of the town_aggregated_water_access CTE would you need to change?

### 3. Which province should we send drilling equipment to first?

### 4. Why was the LEFT JOIN operation used with the well_pollution table in the queries?

### 5. Which towns should we upgrade shared taps first?

### 6. Which of the following improvements is suggested for a chemically contaminated well with a queue time of over 30 minutes?

### 7. What is the maximum percentage of the population using rivers in a single town in the Amanzi province?

### 8. In which province(s) do all towns have less than 50% access to home taps (including working and broken)?

### 9. Using this list, and the data in the md_water_services database, how would you calculate the total cost of all the infrastructure upgrades in Maji Ndogo?

### 10. What does the following query describe?

These SQL queries have been instrumental in extracting specific information, addressing data inconsistencies, and providing insights into various aspects related to the water crisis in Maji Ndogo.