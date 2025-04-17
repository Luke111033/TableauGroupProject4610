# TableauGroupProject4610

## Group Members - Group 4
- [Tobias Allers]()
- [Luke Mabry](https://github.com/Luke111033/TableauGroupProject4610/blob/main/README.md)
- [Alicia Lim]()
- [Chris Sierra]()
- [Pranav Rohit]()

## Data Set: Walkability Index
Link: https://catalog.data.gov/dataset/walkability-index8

## 2 questions:
Q1: How does job accessibility by transit vary across urban and rural block groups?

Why it matters: Highlights public transport coverage equity, economic opportunity access

Data tie-in: Columns like D5ar_Transit (job access via transit), URB_ID (urban/rural type)

Q2: Is there a relationship between vehicle miles traveled (VMT) and population density?

Why it matters: Informs sustainable urban planning, climate policy

Data tie-in: Columns like D1a (population density), D2a_E5 (employment mix), D3bpo4 (VMT per capita)

##Project Outline:
Dataset Description
Title: EPA Smart Location Database (Version 3, January 2021)

Source: Data.gov

Format: CSV file

Observations: ~32,000 Census Block Groups

Features (Columns): ~100 metrics including:

Population and job density

Intersection and street connectivity

Access to jobs via car or transit

Land-use diversity

Vehicle miles traveled (VMT)

Greenhouse gas emissions (GHG)

The dataset is used in urban planning, transportation modeling, and policy evaluation across the U.S.


🔧 Data Manipulations
Dropped rows with missing values in D1a, D3bpo4, and D5ar_Transit.

Created binned ranges for population density.

Grouped data by URB_ID to compare urban and rural areas.

Normalized select variables to compare across regions.

📈 Analysis & Visualizations
Visuals created in Tableau:

Bar chart: Average job access by transit (urban vs rural)

Scatter plot: Population density vs. VMT per capita with trendline

Boxplot or heat map: Regional differences

Implications:

Urban areas have much higher transit accessibility.

Higher density areas generally have lower VMT, supporting compact development strategies.

Visualizations can guide planners in transportation and land-use decisions.

📁 Tableau Packaged Workbook
File: Book1.twb

Visuals included for both questions

Calculated fields and filters applied where needed
