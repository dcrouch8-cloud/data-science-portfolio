## Research Question
## Is Charlotte, North Carolina able to address adequate affordable housing needs in response to population and economic growth?

The analysis uses American Community Survey (ACS) 5-year estimates for the **City of Charlotte, North Carolina** from 2010–2024.

| Variable | ACS Variable | Definition |
|:---|:---:|:---|
| **Population** | `DP05_0001E` | Estimated total population |
| **Median Household Income** | `DP03_0062E` | Median household income in inflation-adjusted dollars |
| **Poverty Rate** | `DP03_0128PE` | Percentage of people below the poverty level |
| **Median Rent** | `DP04_0134E` | Median gross rent among occupied units paying rent |
| **Median Home Value** | `DP04_0089E` | Median value of owner-occupied housing units |
| **Housing Units** | `DP04_0001E` | Total number of housing units |
| **Renter Cost Burden** | `DP04_0141PE + DP04_0142PE` | Percentage of renter-occupied units paying 30% or more of household income toward gross rent |

## Data Cleaning and Preparation
- Rows with missing values are removed although when analysing the data I found that there was not any missing values.
- The two renter cost-burden categories are combined because both represent households spending at least 30% of income on gross rent.

## Exploratory Analysis
The next section answers three practical questions:

1. Did population and housing supply grow at similar rates?
2. Did household income keep pace with rent and home-value growth?
3. Did renter cost burden improve or worsen over time?

[Housing Units vs Population](img1.png)
