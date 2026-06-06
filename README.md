# 🏅 Historical Olympic Data Pipeline & Business Intelligence EDA

## 📌 Project Overview
This end-to-end data engineering and exploratory data analysis (EDA) project processes a raw historical dataset of Summer Olympic Medals (1976–2008). The project handles advanced programmatic data cleaning, standardizes legacy anomalies, engineers a custom performance index, and delivers corporate brand-aligned data stories designed for business stakeholders.

## 🛠️ Tech Stack & Skills Demonstrated
* **Language:** Python 3
* **Libraries:** Pandas, Numpy, Matplotlib, Seaborn
* **Data Engineering:** Missing value imputation, data validation checkpoints, string standardizations, and structural event-level de-duplication.
* **Data Storytelling:** Visual communication using custom corporate color palettes (PwC Orange & Grey) and modern annotation loops.

## 📊 Core Business Insights Uncovered (Q1 - Q5)
1. **Q1: The Closing Gender Gap:** Tracked a monumental structural shift in athlete representation from 1976 to 2008, isolating a massive spike in female podium finishes beginning in the 1996 Atlanta Games.
2. **Q2: The Raw Global Dominance Board:** Established an initial baseline of total medals awarded, mapping out historical superpower dominance (highlighting the USA's massive initial lead of 1,992 total medals).
3. **Q3: The Home-Field Advantage:** Isolated Australia's historical performance to validate the "Host Nation Spike," proving a significant, localized medal volume surge during the Sydney 2000 Games.
4. **Q4: Unmasking Team Sport Inflation:** Developed a robust de-duplication pipeline that collapsed team rosters down to unique event wins. This unskewed the Q2 leaderboard, revealing that over 55% of the USA's raw medal count (dropping to 884) was driven purely by roster inflation.
5. **Q5: The Ultimate MVP Index:** Engineered a weighted scoring algorithm (Gold=3, Silver=2, Bronze=1) to surface the definitive individual outliers of the era, highlighting Michael Phelps' concentrated peak dominance.

## 🚀 Next Steps
The finalized dataset has been exported as a pristine, production-ready CSV, optimized for direct integration into Business Intelligence tools (Tableau / PowerBI) for interactive executive dashboards.

## 📂 Data Source
The raw dataset used for this analysis, **Summer Olympic Medals (1976–2008)**, was publicly sourced from [Kaggle](https://www.kaggle.com/datasets/divyansh22/summer-olympics-medals/data). 
