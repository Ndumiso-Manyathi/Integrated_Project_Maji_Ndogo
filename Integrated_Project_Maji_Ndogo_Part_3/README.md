# Clustering data to unveil Maji Ndogo's water crisis


## Overview:
Part 3 of the Maji Ndogo project focuses on integrating the results of a completed audit aimed at assessing the integrity and accuracy of the database. The audit's objective was to ensure that the stored data aligns with principles of good governance and reliable decision-making.

## Audit Results and Objective:
The recent audit specifically targeted the integrity and accuracy of the data stored in the database. It aimed to verify data accuracy and reliability, crucial for sound decision-making and governance practices. The report confirms that the majority of the data aligns with the established principles.

## Introduction:
Maji Ndogo grapples with water accessibility problems, motivating this project to utilize SQL analysis for impactful solutions. The dataset collected from various sources forms the basis for our investigation.

## Explore Maji Ndogo's Database:
### Unveiling Insights through SQL:
- Conduct SQL queries on specific aspects of the dataset.
- Extract information, perform calculations, and analyze trends to address the water crisis effectively.
### Understanding Relationships:
- The ERD in MySQL showcases relationships among various tables, highlighting primary and foreign keys.
- Notably, the visits table holds a central role, acting as a hub for primary keys like location_id, source_id, and assigned_employee_id, which serve as foreign keys from other tables.

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


## Queries and Analysis:
### Data Integrity Considerations:
- Identifying discrepancies between the expected relationships and the ERD is crucial for maintaining data integrity and resolving potential errors.
- Ensuring that the record_id is unique for both the visits and water_quality tables is vital before modifying the relationships to maintain a one-to-one correspondence.

## Correcting Database Relationships:

### Rectification Process:
- Addressing the disparity between the expected and depicted relationships, particularly between visits and water_quality tables, is essential.
- Verification of the uniqueness of record_id in both tables precedes any adjustments to maintain accurate and reliable data representation.

## Integrated Project Questions:
### Overview of Project Queries:
- Detailed listing of project-related questions with corresponding SQL queries.
- Addressing issues such as employee details, water source analysis, population assessment, and anomaly detection.

## Instructions for Use:
### Guidelines for Contributors and Users:
- Instructions for setting up the project environment and database.
- Guidance on executing SQL queries, understanding dataset nuances, and contributing to the project.

## Answered Queries:

### 1. The following query results in 2,698 rows of data being retrieved, but the auditor_report table only has 1,620 rows. Analyse the query and select the reason why this discrepancy occurs?

### 2. What is the function of Incorrect_records in the following query?

### 3. In the suspect_list CTE, a subquery is used. What type of subquery is it, and what is its purpose in the query?

### 4. A colleague proposed the following CTE as an alternative to the suspect_list we used previously, but it does not give the desired results. What will be the result of this subquery?

### 5. How is the relationship between the employee table and the visits table represented in the ERD?

### 6. Which table contains the location_id as its primary key?

### 7. How would you modify the Incorrect_records CTE to join the well_pollution data?

### 8. Which employee just avoided our classification of having an above-average number of mistakes?

### 9. Which of the following “suspects” is connected to the following civilian statement: “Suspicion coloured villagers' descriptions of an official's aloof demeanour and apparent laziness. The reference to cash transactions casts doubt on their motives.

### 10. Consider the provided SQL query. What does it do?

These SQL queries have been instrumental in extracting specific information, addressing data inconsistencies, and providing insights into various aspects related to the water crisis in Maji Ndogo.