# Methodology

## Objective

Investigate whether health deprivation is associated with higher childhood obesity rates across London boroughs.

## Data Sources

- Trust for London – Health Deprivation and Disability Rank
- NHS England / Fingertips – Childhood obesity prevalence

## Data Preparation

- Downloaded datasets from official public sources.
- Cleaned unnecessary columns in Excel.
- Standardised borough names.
- Used XLOOKUP to combine datasets.
- Removed City of London due to missing obesity data.
- Saved the cleaned dataset as CSV for SQL analysis.

## SQL

- Imported the cleaned dataset into SQLite.
- Created a table.
- Queried borough-level data to validate imports and explore trends.

## Dashboard

Built an interactive dashboard in Looker Studio including:

- Borough comparison
- Scatter plot of deprivation vs obesity
- Summary KPI cards
- Interactive filtering

## Key Findings

- Boroughs with higher health deprivation generally showed higher childhood obesity rates.
- Some boroughs deviated from the overall trend, suggesting additional social and environmental factors.

## Limitations

- Cross-sectional data only.
- Borough-level averages may hide local variation.
- Correlation does not imply causation.

## Future Improvements

- Include multiple years of data.
- Add IMD, income and ethnicity variables.
- Use regression analysis to quantify relationships.
