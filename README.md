# After-covid-macroeconomics
Developing a Power BI visualization tool to identify correlations between data points and the outcomes of their interactions.

**Dataset Source:** [Global Inflation Dynamics Post-COVID (2020-2024)](https://www.kaggle.com/datasets/ssssws/global-inflation-dynamics-post-covid-20202024)

---

## Data Challenges & Processing
During the Exploratory Data Analysis (EDA), I encountered several consistency issues, particularly with the **M2 Money Supply** metrics. It was unclear if values were in local currency or USD. While an "Exchange Rate to USD" column was available, the raw values required significant transformation.

The data cleaning phase was a **"meditative"** process, focusing on:
* **Data Normalization:** Standardizing data types for seamless Power BI integration.
* **Precision Management:** Handling float precision and null values within Power Query.
* **Structural Transformation:** Converting raw economic metrics into functional analytical dimensions.

---

## Key "Anti-Insights" & Data Validation
* **Data Integrity Note:** In the raw dataset, Canada's reported Money Supply appeared larger than that of the USA. Since this indicates non-validated raw data, certain deep-dive opportunities were limited.
* **Logic Preservation:** Despite these discrepancies, the core analytical logic and the relationship-mapping framework within the dashboard remain fully functional and structurally sound.

---

## Technical Stack
* **Tool:** Power BI Desktop
* **Data Engine:** Power Query (M)
* **Visuals:** Shape Maps, Key Influencers (AI-driven), Time-series forecasting, Dynamic Bubble Charts.

---

> **Note:** You can find the project demonstration video `dashB_vid.mp4` in the media folder of this repository.
