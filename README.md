# Melbourne Crime & Liveability Intelligence Dashboard

**Status:** In Progress  
**Tools:** Python · SQL (SQLite) · Tableau Public · GitHub  
**Timeline:** Days 1-14

## Project Overview
Building an interactive Tableau Public dashboard analysing 9 years of Victorian crime statistics across 30 Melbourne LGAs.

## Folder Structure

```text
melbourne-crime-liveability-dashboard/
├── .gitignore
├── README.md
├── data/
│   ├── raw/                 # Downloaded source files (never edit)
│   └── processed/           # Cleaned CSV outputs from Python
├── python/
│   └── clean_data.py       # Data cleaning scripts
├── sql/
│   └── analysis_queries.sql # SQL analysis queries
├── tableau/
│   └── melbourne_dashboard.twbx  # Tableau workbook package
├── insights/
│   └── key_findings.pdf     # Key findings summary
└── .git/                   # Git metadata
```
## 📊 Tableau Dashboard

**Live Dashboard:** https://public.tableau.com/app/profile/animesh.dubey3953/viz/MelbourneCrimeLiveabilityIntelligenceDashboard/Dashboard1

### Dashboard Features:
- 🔴 **KPI Cards** - Total incidents, crime rates, safest/highest areas
- 📈 **Crime Trend Line** - Melbourne-wide trend (2015-2024)
- 🔴 **Top 10 Highest Crime LGAs** - Bar chart showing most dangerous areas
- 🟢 **Top 10 Safest LGAs** - Bar chart showing safest suburbs
- 🗺️ **Heat Map** - Crime by LGA and year visualization
- 🥧 **Pie Chart** - Crime distribution across regions
- 📊 **2015 vs 2024 Comparison** - Year-over-year analysis

### Key Insights:
- Melbourne had **315,073 total incidents** in 2024
- Average crime rate: **6,592 per 100,000 population**
- Safest rate: **2,728** (Nillumbik area)
- Highest rate: **19,331** (Melbourne CBD)
- Crime trends show variation across Melbourne LGAs over 10 years

### How to Use the Dashboard:
1. Click the link above to view the live dashboard
2. Hover over charts to see detailed values
3. Click chart elements for interactive exploration
4. Use filters to drill down into specific years or regions
