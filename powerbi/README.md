# Power BI Dashboard

![Demo](../assets/powerbi-demo.gif)

Star-schema model: QuarterTable (bridge) connected to Model_Data, 
BudgetVsActual, Forecast, Commentary, and CashFlow (via YearTable).

## Key DAX

- CALCULATE-based measures for Total Sales, Expenses, Operating Profit
- TREATAS for cross-grain Year filtering (Cash Conversion %)
- Custom fiscal-year quarter labeling (April-start FY)

Open `britannia_dashboard.pbix` in Power BI Desktop to explore interactively.