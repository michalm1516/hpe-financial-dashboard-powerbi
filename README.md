# HPE Financial Performance Dashboard FY2023–2025 (Power BI)

An interactive Power BI dashboard showing Hewlett Packard Enterprise's financial performance over three fiscal years, in USD millions.

![Dashboard](dashboard.png)

## Business question

How have HPE's revenue, profitability and segment mix developed between FY2023 and FY2025?

## What the dashboard shows

- **KPI cards:** net revenue, net earnings, gross margin % and operating margin %
- **Combo chart:** revenue (columns) against gross margin % (line) by fiscal year
- **Segment chart:** revenue by business segment
- **Fiscal year slicer:** filters every visual on the page

## Data model

| Table | Columns |
|---|---|
| `Income_Statement` | Fiscal_Year, Net_Revenue, Net_Earnings and other income statement lines |
| `Segments` | Fiscal_Year, Segment, Revenue |

DAX measures: `Gross Margin %`, `Operating Margin %`.

## Skills demonstrated

- Data modelling in Power BI (two related tables)
- DAX measures for margin KPIs
- Dashboard design: KPI cards, combo chart, bar chart, slicer
- Financial statement analysis (revenue, margins, earnings)

## Files

- `Dashboard.pbix` - the Power BI report (open in Power BI Desktop)
- `dashboard.png` - screenshot of the report page

## Author

Michał Mucha - Economic Analytics student, Wrocław University of Economics and Business
[LinkedIn](https://www.linkedin.com/in/micha%C5%82-mucha-4692872b9/)
