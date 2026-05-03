# After-covid-macroeconomics
Developing a Power BI visualization tool to identify correlations between data points and the outcomes of their interactions.

Dataset Overview
This dataset focuses on key macroeconomic indicators in the post-pandemic period, covering the timeframe from January 1, 2021, to January 1, 2024.
The analysis is based on open-source data: Global Inflation Dynamics Post-COVID (2020-2024).

Data Challenges & Processing
During the initial EDA (Exploratory Data Analysis), I encountered several data consistency issues, particularly regarding the M2 Money Supply column. It was unclear whether the values were represented in local currency or USD. While the "Exchange Rate to USD" column was intended to clarify this, the raw values required significant aggregation and transformation to become usable.

The data cleaning phase was a "meditative" process, involving:

Standardizing data types for seamless Power BI integration.

Handling float precision and null values in Power Query.

Transforming raw economic metrics into analytical dimensions.

Key "Anti-Insights" & Data Validation

Data Integrity Note: In the raw dataset, Canada's reported Money Supply appeared larger than that of the USA. Since this suggests non-validated or misaligned raw data, certain deep-dive analytical opportunities were limited.

Logic Preservation: Despite these data discrepancies, the core analytical logic and the relationship-mapping framework within the dashboard remain fully functional and structurally sound.
