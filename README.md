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