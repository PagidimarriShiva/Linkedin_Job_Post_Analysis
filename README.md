# 📊 LinkedIn Job Market Analysis – Power BI Dashboard 
## Table of Contents

### Project Overview

- Data Source
- Tools Used
- Data Cleaning & Preparation
- Exploratory Data Analysis
- Data Analysis
- Results
- Recommendations
- Limitations

## 📌 Project Overview

This project analyzes LinkedIn job postings data to uncover insights into hiring trends, in-demand skills, remote work patterns, and company-level recruitment activity.

Using Power BI, I designed two interactive dashboards:

Overview Dashboard – High-level job market trends and KPIs

Skills & Talent Demand Dashboard – Skill demand, experience requirements, and role–skill relationships

Designed a salary insights tooltip page to provide contextual salary and experience information across dashboards

The dashboards are designed for recruiters, HR teams, workforce planners, and business stakeholders to support data-driven hiring decisions.

## 📂 Data Source

Dataset: LinkedIn Job Postings (2024–2025)

Size: ~500,000 job postings

### Format: CSV

### Key fields:

- Job Title
- Company Name
- Industry
- Location
- Posted Date
- Employment Type
- Remote Type
- Skills Required
- Experience Required
- Salary Range (where available)

Note: The dataset represents publicly available job postings and may not reflect all hiring activity.

## 🛠️ Tools Used

Power BI Desktop

Power Query (ETL)

DAX (Measures & Calculations)

Data Modeling (Star Schema)

Microsoft Excel (initial data inspection)

GitHub (project versioning & documentation)

## 🧹 Data Cleaning & Preparation

Data preparation was performed using Power Query and included:

Converting data types (dates, numeric fields)

Parsing and splitting location into city, state, and country

Normalizing text fields (job titles, industries, companies)

Expanding skills_required into individual skill records

Extracting minimum and maximum salary values where possible

Removing duplicate and irrelevant columns

Creating dimension tables (Date, Company, Location, Skills)

A star schema was implemented to improve performance and simplify analysis.

## 🔍 Exploratory Data Analysis

Initial EDA focused on understanding:

Distribution of job postings across industries and locations

Growth trends over time

Remote vs onsite job distribution

Common job titles and experience requirements

Skill frequency and co-occurrence patterns

These insights guided the dashboard design and KPI selection.

## 📈 Data Analysis

Key analyses performed using DAX measures include:

Total job postings and recent job trends

Percentage of remote and hybrid roles

Average experience required by role and industry

Top hiring companies and industries

Most in-demand skills across job titles

Skill-to-role relationships using interactive visuals

Advanced Power BI features used:

Slicers and synced filters

Drillthrough pages

Tooltip pages

Dynamic titles

Bookmarks and navigation buttons

## 📊 Results

### Key insights from the dashboards:

Remote and hybrid roles continue to represent a significant share of postings

Technology and analytics roles dominate job demand

Skills such as SQL, Python, Power BI, and communication skills are consistently in high demand

Hiring activity is concentrated among a small number of large companies

Higher experience requirements correlate with specialized technical skills

## ✅ Recommendations

### Based on the analysis:

Job seekers should prioritize learning high-demand skills identified in the dashboard

Recruiters can benchmark skill requirements against industry trends

Companies can use the insights to refine workforce planning strategies

HR teams can identify emerging roles and skill gaps

## ⚠️ Limitations

Salary data is incomplete and inconsistently formatted

Skill listings depend on employer-provided descriptions

Dataset reflects postings, not actual hires

Location data may vary in granularity

The analysis is limited to the available time period

## 📎 Future Enhancements

Add Row-Level Security (RLS)

Incorporate additional time-based trend analysis

Publish dashboards to Power BI Service

Integrate external labor market datasets
