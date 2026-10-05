# Purchases & Costs Dashboard (Power BI)

Interactive Power BI report analyzing purchase volumes and product costs, built from a hands-on exercise for a Master's in Data Analytics.

## Data Model

Two related tables, joined by product ID:

- **Purchases (Compras)** — purchase transactions with quantity per product.
- **Costs (Costos)** — product catalog with unit cost, quality, calories, origin, and vendor.

## Measures

- Total purchased quantity per product.
- Revenue measure combining purchased quantity and unit cost.
- A filtered revenue variant, driven by an interactive filter/button control on the report page.

## Visualizations

- Table views combining purchase quantities with unit costs to compute revenue per product.
- Full product catalog table (cost, quality, calories, origin, vendor).
- Action buttons for interactive filtering between report views.

## Tools

- Power BI Desktop
- DAX

## How to View It

1. Download the `fruta.pbix` file from this repository.
2. Open it with [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads) (free).

## Author

**Álvaro Rubio Milán**
Physics graduate · Junior Data Analyst
[LinkedIn](https://linkedin.com/in/alvaro-rubio-milan-8736b22a8)

## Notes

Developed as part of a data analytics portfolio, based on an exercise from a Master's in Data Analytics. The data is fictitious/generated for the exercise.
