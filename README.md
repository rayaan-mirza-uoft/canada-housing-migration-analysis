# Housing Price Growth and Interprovincial Migration Analysis in Canada (2010–2025)

## Project Overview

This project explores the relationship between provincial housing price growth (HPI growth) and interprovincial migration rates across Canadian provinces from 2010 to 2025.

The objective is to determine whether migration inflows are associated with higher housing price growth at the provincial level.

## Research Question

Is there a measurable relationship between interprovincial migration rates and provincial housing price growth?

## Data Sources

- Provincial House Price Index (HPI)
- Interprovincial migration flows
- Provincial population data (used to compute migration rates)

All data were reshaped and merged into a province–year panel dataset.

## Methodology

1. Converted monthly HPI data to annual growth rates.
2. Extracted annual migration flows.
3. Normalized migration flows by provincial population to construct migration rates.
4. Merged datasets into a balanced panel (Province × Year).
5. Conducted:
   - Summary statistics
   - Correlation analysis
   - Distribution analysis (histograms)
   - Time-series visualization
   - Scatter plot with fitted regression line

## Key Findings

- The correlation between migration rate and HPI growth is positive but weak (~0.19).
- Migration effects appear small relative to broader macro housing cycles.
- Significant housing growth spikes (e.g., 2021–2022) are not fully explained by migration patterns alone.

## Repository Structure

Migration_Housing_Notebook.ipynb → Full reproducible notebook  
Migration_Housing_Notebook.pdf → Exported notebook (clean view)  
Project_Report.pdf → Written summary document  

## Reproducibility

The notebook can be executed using the following libraries to reproduce all tables and figures.

Required libraries:
- pandas
- numpy
- matplotlib

## Author

Rayaan Mirza  
University of Toronto Mississauga  
Financial Economics