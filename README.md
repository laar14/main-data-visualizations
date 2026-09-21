# main-data-visualizations
National Park Service Visitor Use Statistics
📌 Project Overview
This repository contains two datasets used for exploratory data analysis, state‑level comparisons, and data visualization. The goal of this project is to demonstrate practical analytics workflows using R, Python, and modern visualization libraries.

The project includes:

Raw data files (Main_Data.csv, Main_State_Data.csv)

Scripts for cleaning, summarizing, and visualizing the data

Example charts generated from both datasets

Documentation to help others understand and reproduce the analysis

Repository Structure

project-folder/
│
├── data/
│   ├── Main_Data.csv
│   └── Main_State_Data.csv
│
├── scripts/
│   ├── analysis_R.R
│   └── analysis_Python.ipynb
│
├── visuals/
│   ├── histogram_main_data.png
│   ├── state_summary_plot.png
│   └── additional_visuals.png

Main_Data.csv
This dataset contains record‑level or aggregated metrics used for exploratory analysis.
Example types of fields (actual names will vary):

Date fields — reporting periods, encounter dates

Numeric metrics — counts, rates, utilization values

Categorical fields — facility, region, category, type

Outcome variables — performance indicators or event counts

Main_State_Data.csv
This dataset contains state‑level summaries.
Typical fields may include:

State — jurisdiction name

Aggregated metrics — averages, totals, per‑capita values

Comparative indicators — rankings, percent change, severity levels

Visualizations Included
The repository contains example visuals created in both R and Python, such as:

Distribution plots (histograms, density curves)

State‑level comparison charts

Trend lines over time

Bar charts and heatmaps

