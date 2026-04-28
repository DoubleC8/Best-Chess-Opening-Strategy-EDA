# Exploratory Data Analysis: Foundational Chess Strategy

## Executive Summary

Analyzed over 20,000 online chess matches to identify statistically dominant strategies within beginner skill brackets (<1500 Elo). Using Python and Pandas, the data was cleaned and aggregated to prove that White maintains a ~5% first-mover advantage, with the Scandinavian Defense: Mieses-Kotroc Variation yielding the highest win probability for White among the top 10 most popular openings.

## Methodology & Skills

- **Data Wrangling (Pandas):** Filtered a large dataset to isolate specific target audiences (beginner brackets) and applied logical conditions to calculate baseline win rates.
- **Data Aggregation:** Utilized `.groupby()` functions to efficiently calculate complex probabilities across segmented categories without relying on slow `for` loops.
- **Data Visualization (Seaborn/Matplotlib):** Transformed raw pandas Series data into a sorted, presentation-ready horizontal bar chart to communicate findings to non-technical stakeholders.
