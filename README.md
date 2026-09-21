National Park Service Visitation Analysis
This project analyzes National Park Service (NPS) monthly visitation statistics using R. The dataset includes visitation counts for every major NPS unit across multiple decades, broken down by specific visitation types (e.g., recreation visits, backcountry nights, concessioner lodging, trail use).

📁 Repository Structure
Code
Main data visualization/
│
├── data/
│   ├── Main_Data.csv
│   ├── Main_State_Data.csv
│
├── scripts/
│   └── analysis_R.R
│
├── visuals/
│   ├── histogram_monthly_visitation.png
│   ├── avg_monthly_visitation_by_state.png
│   ├── monthly_visitation_trend.png
│   └── total_visitation_by_statistic.png
│
└── README.md
📊 Visualizations Included
1. Distribution of Monthly Visitation Counts
Shows how visitation numbers vary month‑to‑month across all parks and all statistic types.
The distribution is highly skewed due to many months with low or zero activity.

2. Average Monthly Visitation by State
Ranks states by average monthly visitation across all parks.
Nevada leads due to Lake Mead NRA’s extremely high visitation.

3. Monthly Visitation Trend Over Time
Displays long‑term visitation trends across decades.
Seasonal spikes represent summer peaks; post‑1990 changes reflect reporting shifts.

4. Total Visitation by Statistic Type
Compares total visitation counts across all statistic categories.
Total Hours (TH) and Total Recreation Vehicle Hours (TRVH) dominate.

📘 Data Dictionary
A full data dictionary explaining each visitation statistic is included in data_dictionary.md.

🛠 Tools Used
R

tidyverse

ggplot2

dplyr

RStudio

**Data Analyst / Health Data Scientist**

[GitHub Profile](https://github.com/laar14)  
[LinkedIn Profile](https://www.linkedin.com/in/liyerpt/)



