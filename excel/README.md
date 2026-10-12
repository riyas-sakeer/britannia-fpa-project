# Excel Model

![Dashboard](../assets/excel-dashboard.png)
![budgetvsactual](/assets/budget-actual-excel.png)
![Commentory](/assets/commentory-excel.png)
## Sheets

- **Dashboard** — KPI cards, 10-year trend, budget vs actual, forecast, driver commentary
- **Model_Data** — clean long-format source data (Power Query output)
- **Budget vs Actual** — dynamic XLOOKUP + EDATE prior-year comparison
- **Forecast** — OFFSET-based rolling 4-quarter average growth, dropdown-driven (Data Validation + IFS)
- **Commentary** — auto-ranked top variance drivers (LARGE + INDEX/MATCH)