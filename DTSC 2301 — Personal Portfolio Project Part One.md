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

1. Did household income keep pace with rent and home-value growth?
2. Did renter cost burden improve or worsen over time?
3. Did population and housing supply grow at similar rates?

![Photo](img1.png)
The graph shows that income, rent, and home values in Charlotte, NC all increased from 2015 to 2024. Home values had the biggest increase, while rent also increased significantly. Although median household income increased, it did not grow as quickly as rent and home values. This could suggest that housing became less affordable for Charlotte residents over time.


![Photo](img2.png)
The graph shows that Charlotte's renter cost burden decreased between 2015 and 2020, but started increasing after 2020. By 2024, almost 50% of renter households were spending at least 30% of their income on rent. This shows that rent has become a growing financial burden for many Charlotte renters. The increase after 2020 may also suggest that housing affordability became a bigger issue in Charlotte in the years following the pandemic.



