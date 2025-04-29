# TableauGroupProject4610

## Group Members - Group 4
- [Tobias Allers](https://github.com/tka29934/MIST-4610-project-2)
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
"How does the distribution of vehicle ownership differ between Eastern and Western U.S. regions in medium-to-high density neighborhoods, and what does this reveal about regional differences in urban planning and transportation access?"

This question examines how vehicle ownership patterns vary across regions even when population density is held constant. By comparing medium- and high-density block groups between the East and West, we can explore how infrastructure, public transit availability, and walkability contribute to car dependence or independence. While high-density areas typically reduce the need for cars, this may not hold equally across all regions due to planning and transit differences. The visualization helps highlight how geography influences transportation behavior beyond just density.

Why it matters: Regional gaps in vehicle access reflect broader differences in transit investment and planning priorities. Understanding these patterns supports better policymaking for equitable mobility and infrastructure development.

Data used:

D1B: Gross population density (people per acre)

Pct_AO0: Percent of households with zero vehicles

Statefp: Used to assign East or West region labels

![image](https://github.com/user-attachments/assets/e8bde08c-6994-4ba9-860e-4c6b118295a3)

## Project 2 – Group Question 2
Do areas with more diverse land use tend to have lower vehicle miles traveled per capita?

This question looks at how the mix of land uses (e.g. jobs, services, housing) within an area affects travel behavior. Denser and more mixed-use areas are theorized to support shorter trips and more walking or transit usage.

Why it matters: Mixed-use areas where jobs, services, and housing, are can reduce the need for long vehicle trips, encouraging walking, biking, or transit use. Reducing VMT is also vital for cutting greenhouse gas emissions and combating climate change. This analysis can support sustainable planning by identifying how mixed-use development might reduce car dependence and emissions.

Data used:

D2B_E5MIX: Land use diversity index (employment-based)

D3BPO4: Vehicle miles traveled (VMT) per capita

Planned analysis: Scatter plot of D2B_E5MIX vs. D3BPO4 to identify trends or correlations.

Expected visualization: Scatter plot in Tableau.



