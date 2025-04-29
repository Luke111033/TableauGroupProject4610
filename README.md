# TableauGroupProject4610

## Group Members - Group 4
- [Tobias Allers]()
- [Luke Mabry](https://github.com/Luke111033/TableauGroupProject4610/blob/main/README.md)
- [Alicia Lim](https://github.com/alicianlim/Project-2-4610)
- [Chris Sierra](https://github.com/Chrissi3rraa/4610-Project-2)
- [Pranav Rohit]()

## Data Set: Walkability Index
Link: https://catalog.data.gov/dataset/walkability-index8

Description: 
Our project utilizes data from the Smart Location Database (SLD), developed by the U.S. Environmental Protection Agency (EPA). The SLD provides a nationwide, standardized dataset at the Census block group level, offering an array of variables that describe characteristics of the built environment, transportation systems, and demographics. This dataset is particularly well-suited for exploring how urban form and accessibility influence transportation behavior.

Source: Smart Location Database (Version 2.0, EPA)
Level of Detail : Census Block Group Level (~220,000 block groups across the U.S.)
Dimensions: Approximately 220,000 rows (one per block group), 100+ columns (variables)

## 2 questions:
## Project 2 – Group Question 1
"To what extent do population density, intersection density, and transit accessibility together explain differences in vehicle ownership across U.S. neighborhoods?"

This question explores the relationship between access to private transportation and the density of an area. Areas with higher population density may offer better transit infrastructure, reducing the need for personal vehicles. On the other hand, rural areas often lack public transit, making vehicle ownership essential. This data visualization can answer questions regarding the changes necesssary for more inclusive public transit infrastructure in the United States.

Why it matters: This ties directly into social and economic accessibility. Mixed-use areas—where jobs, housing, and services co-exist—can reduce the need for long vehicle trips, encouraging walking, biking, or transit use. Reducing VMT is also vital for cutting greenhouse gas emissions and combating climate change. Households without vehicles face limited job access and daily mobility challenges.

Data used:

D1A: Gross population density

Pct_AO0: Percent of households with zero vehicles

Planned analysis: Categorize block groups into Urban, Suburban, and Rural using D1A, then compare Pct_AO0 across those bins.

Expected visualization: Bar chart or boxplot showing the percent of households with no vehicles by density category.

## Project 2 – Group Question 2
Do areas with more diverse land use tend to have lower vehicle miles traveled per capita?

This question looks at how the mix of land uses (e.g. jobs, services, housing) within an area affects travel behavior. Denser and more mixed-use areas are theorized to support shorter trips and more walking or transit usage.

Why it matters: This analysis can support sustainable planning by identifying how mixed-use development might reduce car dependence and emissions.

Data used:

D2B_E5MIX: Land use diversity index (employment-based)

D3BPO4: Vehicle miles traveled (VMT) per capita

Planned analysis: Scatter plot of D2B_E5MIX vs. D3BPO4 to identify trends or correlations.

Expected visualization: Scatter plot with a trendline in Tableau.



