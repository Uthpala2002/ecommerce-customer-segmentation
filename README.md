# E-commerce Customer Segmentation

End-to-end customer segmentation project using SQL (RFM analysis)
and K-Means clustering on the UCI Online Retail II dataset
(~800K transactions, ~5,900 customers).

## Dataset
[UCI Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii)
(raw file not included here due to size — see notebooks/01 for cleaning code)

## Project structure
- notebooks/01_Data_cleaning.ipynb   — clean raw transaction data
- notebooks/02_sql_setup.ipynb       — SQLite database + RFM SQL queries
- notebooks/03_clustering.ipynb      — K-Means clustering + segment naming
- outputs/                           — RFM table, final segments, summary

## Status
- [x] Data cleaning (Python/pandas)
- [x] SQL database + RFM queries (SQLite)
- [x] K-Means clustering and segment profiling
- [ ] Streamlit dashboard

## Tech stack
Python, pandas, scikit-learn, SQLite, Streamlit (coming)
