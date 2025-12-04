# NHL Analytics: Identifying the Key Factors Behind Team Wins

This repository contains our NHL analytics project, where we analyze team statistics such as goal differential and shootout wins to determine which factors are most strongly associated with total wins. It includes cleaned datasets, visualizations, and statistical analyses used to support our findings.

## Overview

Using publicly available NHL team statistics, we examine the relationship between team performance metrics and overall success to better understand what drives winning outcomes in the league. Our analysis uses exploratory data analysis and visualization techniques to uncover patterns and relationships between on-ice performance and win totals, allowing us to identify which statistics appear to have the strongest connection to team success. Through this project, we aim not only to gain insights into the factors that separate top-performing teams from the rest of the league, but also to strengthen our skills in data cleaning, analysis, visualization, and collaborative interpretation of real-world sports data.

### Interesting Insight (Optional)

This is optional but highly recommended. You'll include one interesting insight from your project as part of the README. This insight is most effective when you include a visual. Keep in mind that this visual must be included as an image file (e.g., JPG, PNG, etc.). You can export plots created with `{ggplot2}` by using the function `ggsave`.

## Data Sources and Acknowledgements

The data used for this project was sourced from the Score Network NHL dataset for the 2022–2023 season, https://data.scorenetwork.org/hockey/nhl_2223.html, which provides publicly available team-level performance statistics across the league. This dataset includes detailed measures of team outcomes and on-ice performance that support our exploratory analysis of which factors most strongly relate to winning games. The data is openly accessible and maintained as part of the Score Network Hockey data repository.

We used the following categories of statistics from the dataset:
Team performance data – Win totals, goals for and against, and goal differential.
Game outcome indicators – Shootout outcomes and overtime results.
Special teams metrics – Power-play and penalty-kill efficiencies where available.
Summary team metrics – Aggregated values used to evaluate trends across the league.

These datasets were cleaned and prepared for analysis prior to visualization and modeling. By focusing on team-level measures rather than individual player statistics, our project emphasizes identifying league-wide patterns that best explain overall team success.

## Current Plan

1. Data Collection – Gather publicly available NHL team statistics from sources such as GitHub and Score Network and compile them into a single dataset for analysis.

2. Data Cleaning – Check for missing values, inconsistencies, and formatting issues, and organize the data to ensure accuracy and usability.

3. Exploratory Data Analysis (EDA) – Create summary statistics and visualizations to explore relationships between team performance metrics and total wins.

4. Analysis - Examine trends identified during EDA and apply basic statistical methods to determine which metrics are most strongly associated with team success.

5. Visualization – Develop clear charts and graphics to communicate our findings and write summaries explaining the results.

6. Review – Collaborate as a team to refine the analysis, address limitations, and update findings based on peer feedback.

7. Final Documentation – Compile all code, visualizations, and conclusions into a polished final report within the repository, with references to our detailed project plan for additional context.

## Repo Structure

All .csv files in this repository contain the raw NHL team statistics we collected from publicly available online data sources and serve as the primary datasets used for our analysis. These files provide the foundation for data cleaning, visualization, and statistical evaluation throughout the project. Some files in the repository, such as the project guidelines document, were carried over from the original template repository that was used to initialize this project.

The most important file is our .qmd (Quarto) document, which contains the complete workflow for the project, including data wrangling code, exploratory analysis, visualizations, and written interpretation. This file was used to generate the final .pdf report that was submitted for the project and has the largest number of commits because it represents the core collaborative work produced by our team.

## Authors

Mason Spikula (mrs7283@psu.edu) Kyle Jablonsky (kkj5303@psu.edu) Harshini Mallipedhi (hqm5380@psu.edu)
