# H1B LCA Data Engineering Project
This project aims to build an end-to-end data pipeline and analytics on the H1B LCA Disclosure data (2020-2024).
Introduction
What is H1B Data?
H1B visas allow U.S. employers to hire foreign professionals in specialized fields such as IT, finance, healthcare, and engineering. Before an employer can sponsor a potential H1B worker, they must file a Labor Condition Application (LCA) with the U.S. Department of Labor. Each LCA disclosure includes details about the job title, employer, wage, and worksite, creating a large dataset of sponsorship trends.

Why Does It Matter?
Workforce Insights
The H1B program shines a light on in-demand skills across U.S. industries. By analyzing wage data, job roles, and geographic distribution, we see which tech stacks or business sectors are most reliant on foreign talent.
Economic Impact
H1B hires can affect local labor markets, wage levels, and overall economic growth. LCAs provide a tangible record of the wages employers are willing to pay, revealing how companies value specialized expertise.
Policy Analysis
Governments and researchers track filing volumes, wage norms, and job categories to shape immigration and labor policies. Shifts in application numbers can signal skill shortages, industry booms, or the impact of changing legislation.
Project Overview
In this project, we take over 3.5 million H1B LCA records (2020–2024) and build a Data Engineering pipeline that:

Ingests raw CSV data and cleans it (handling missing values, normalizing wage units, etc.).
Transforms it by mapping state abbreviations, NAICS codes (industry classifications), and applying additional data enhancements.
Loads the refined dataset into a PostgreSQL database with a well-defined schema (e.g., splitting out employers and job_postings).
Analyzes the data to uncover industry, wage, and geographic insights—potentially visualized in Tableau/Power BI or a custom Python dashboard.
This end-to-end pipeline demonstrates how real-world data can be tamed and structured for analysts, data scientists, and policymakers who need accurate, reliable information to drive decisions. It also serves as a practical portfolio project, highlighting key Data Engineering skills such as data cleaning, database design, ETL, and (optionally) workflow orchestration with Airflow.
