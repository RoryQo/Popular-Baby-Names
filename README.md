# Popular Baby Names Analysis

## Overview

This R script analyzes baby name data using the `babynames` library. The project focuses on trends in baby names over the years, specifically analyzing the name "Taylor" and identifying common male names along with their median ages. It also includes visualizations to represent the findings effectively.

## Libraries Used

- **babynames**: For accessing historical baby name data.
- **dplyr**: For data manipulation and summarization.
- **ggplot2**: For creating visualizations.

## Key Analyses

### 1. Analysis of the Name "Taylor"

- Filtered the dataset to find occurrences of the name "Taylor" over the years.
- Summarized data to calculate:
  - Total occurrences (`N`)
  - Total births (`total`)
  - Number of boys with the name (`boys`)
  - Difference from an even gender distribution (0.5)
- Displayed the top 10 years where the ratio of boys to total births was closest to 0.5.

### 2. Common Male Names Analysis

- Created a dataset of the 25 most common male names that are estimated to be alive today.
- Calculated:
  - Estimated number of living individuals for each name.
  - Quartiles and median ages.
- Produced a horizontal bar plot to visualize median ages alongside the interquartile range.

### 3. Additional Insights

- Identified the year with the maximum number of total births (1957).
- Analyzed names from the 1990s to find the top 10 names with the highest occurrences.

## Visualization

- The `m_plot` variable contains a ggplot visualization of median ages for the 25 most common male names, including quartiles for better context.
- Custom aesthetics are used for better clarity and presentation.

  ![Median Ages for Males with the 25 Most Common Names](https://github.com/RoryQo/Popular-Baby-Names/blob/main/graph1.jpg)

## Data Summary

The dataset provides insights into the popularity of baby names over time and how gender distributions have changed.

## Installation

Make sure to install the necessary R packages if you haven't already:

