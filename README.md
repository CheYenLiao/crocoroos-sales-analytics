# Crocoroos Sales Analytics

An academic e-commerce analytics project using SQL Server, SQL Server Integration Services (SSIS), and dimensional modeling to analyze customer revenue and territorial profitability.

## Business Questions

- Who are the top five customers in Australia by revenue?
- What is the monthly revenue from New Zealand?
- Which territories generate the highest total profit across the available data?

## Tools and Skills

- **SQL Server:** Analytical queries using joins, aggregation, filtering, and sorting.
- **SSIS:** Data extraction, transformation, and loading.
- **Dimensional Modeling:** Fact and dimension table design at the order-item level.

## Project Approach

1. Designed a dimensional model with an order-item-level sales fact table and supporting dimensions for customers, products, suppliers, locations, orders, and order items.
2. Built SSIS data flows using OLE DB sources and destinations, sorting, merge joins, lookups, and derived columns.
3. Calculated revenue, product cost, and profit.
4. Wrote SQL queries to rank customers, summarize monthly revenue, and compare territorial profitability.

## Metric Definitions

- **Revenue:** Item quantity × sales price.
- **Product cost:** Item quantity × cost price.
- **Profit:** Revenue − product cost. This measure excludes freight and other operating expenses.

## Project Evidence

The project report documents the dimensional model, SSIS workflows, SQL queries, and query output screenshots.

Additional SQL scripts and screenshots will be added as separate files for easier review.

## Limitations

- This project was completed as an academic case study.
- The original database is not included. Running the queries requires the corresponding SQL Server tables and data.
- The territory profitability query covers all available dates rather than a specific year.
- The analysis supports business decision-making; it does not demonstrate measured improvements in business performance.

## Author

Polly (Che-Yen) Liao
