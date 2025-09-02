# COVID-19 Impact Analysis Dashboard

This repository contains a COVID-19 Global Impact Analysis Dashboard built with **Streamlit** and **Plotly**, using official datasets published by the **World Health Organization (WHO)**.  
The dashboard provides an interactive way to analyze the pandemic’s effects worldwide, enabling users to explore cases, deaths, trends, and mortality rates across regions and countries.

---

## Problem Statement
To create a dashboard that enables users to:

- Monitor global and regional COVID-19 case and death trends  
- Compare countries by cases, deaths, and mortality rates  
- Analyze daily and weekly trends over time  
- Gain insights through interactive visualizations and downloadable reports  

---

## Features of the Dashboard

### Slicers & Filters
- Filter data by **date range**  
- Filter by **WHO region**  
- Filter by **country**  
- Toggle between **Cumulative / Daily / Weekly** views  
- Options for **logarithmic scale** and **trend lines**  

### KPI Cards
- Total Cases  
- Total Deaths  
- New Cases (Daily/Weekly)  
- Mortality Rate (%)  
- Number of Affected Countries  

### Visualizations
- **Animated Map:** Global spread of COVID-19 over time  
- **Bar Charts:** Top 10 countries by cases and deaths  
- **Scatter Plot:** Case-Death relationship with mortality rate  
- **Line Charts:** Trends of cases and deaths over time  
- **Area Charts:** Regional breakdown of cases by WHO regions  
- **Pie Charts:** Distribution of cases and deaths by regions  
- **Treemap:** Hierarchical view by continent, region, and country  
- **Radar Chart:** Multi-dimensional comparison of countries  
- **Data Table & Export:** Download processed data in CSV, Excel, or JSON  

### Data Export
- Export filtered datasets to **CSV**  
- Export to **Excel (XLSX)**  
- Export to **JSON** for API integration  

---

## Tech Stack
- **Python (Pandas, NumPy)**  
- **Streamlit** (Dashboard UI)  
- **Plotly** (Interactive Visualizations)  
- **OpenPyXL** (Excel export)  
- **Jupyter Notebook** (Exploratory Data Analysis)  

---

## Data Source
- [World Health Organization (WHO) COVID-19 datasets](https://covid19.who.int/data)

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/covid-19-impact-analysis.git
   cd covid-19-impact-analysis
