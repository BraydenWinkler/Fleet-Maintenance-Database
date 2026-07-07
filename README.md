# Fleet Maintenance Database

## Project Overview

This project demonstrates the design and implementation of a relational MySQL database used to analyze fleet maintenance records. The objective was to identify maintenance trends, regional failure patterns, and frequently replaced vehicle parts using SQL.

The project was completed as part of my Information Technology coursework and showcases database design, SQL development, data analysis, and technical documentation.

---

## Business Problem

Fleet management companies generate thousands of maintenance records each year. Without proper analysis, identifying recurring failures and preventative maintenance opportunities can be difficult.

This project demonstrates how SQL can transform maintenance records into actionable business intelligence that supports operational decision-making.

---

## Objectives

- Design a relational MySQL database
- Import maintenance data into SQL
- Analyze maintenance trends
- Identify regional maintenance differences
- Determine common replacement reasons
- Produce recommendations for fleet managers

---

## Technologies Used

- MySQL
- SQL
- Relational Databases
- Database Design
- Data Analysis

---

## Skills Demonstrated

- SQL Queries
- CRUD Operations
- GROUP BY
- ORDER BY
- COUNT()
- Data Import
- Database Design
- Database Normalization
- Business Intelligence
- Technical Documentation

---

## SQL Concepts Used

- CREATE TABLE
- LOAD DATA INFILE
- SELECT
- WHERE
- GROUP BY
- ORDER BY
- COUNT
- Filtering
- Aggregation

---

## Business Analysis

The maintenance records were analyzed to identify:

- Frequently replaced vehicle parts
- Regional maintenance trends
- Corrosion-related failures
- Mechanical failures
- Preventative maintenance opportunities

The analysis was translated into recommendations that could help improve maintenance scheduling and reduce vehicle downtime.

---

## Challenges Encountered

During development, several SQL queries referenced incorrect column names.

To resolve this issue, I inspected the database schema using:

```sql
SHOW COLUMNS FROM PartsMaintenance;
```

After identifying the correct column names, the SQL queries were updated accordingly.

This experience strengthened my understanding of schema validation and SQL troubleshooting.

---

## Future Improvements

- Add an Entity Relationship Diagram (ERD)
- Expand analytical SQL reports
- Create dashboards using Power BI or Tableau
- Automate reporting using Python

---

## Author

Brayden Winkler

Bachelor of Science in Information Technology

Southern New Hampshire University
