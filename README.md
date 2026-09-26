# Supply Chain Delivery Performance Analysis

## Project Overview

This project analyzes supply chain delivery performance using the SCMS Delivery History Dataset.

The analysis focuses on shipment delays, delivery performance, shipment modes, countries, fulfillment methods, product groups, and shipment value.

Python was used for data cleaning and exploratory analysis, while Power BI was used to create an interactive dashboard for visualization and reporting.

## Tools Used

- Python
- Pandas
- Jupyter Notebook
- Power BI
- GitHub

## Key Analysis

- Delivery delay rate was analyzed across countries, shipment modes, fulfillment methods, product groups, and years.
- Countries were compared using delivery delay rates, with a minimum shipment threshold applied to avoid conclusions from very small samples.
- Shipment modes were evaluated based on shipment volume, delay rate, and average delay days.
- Product groups were analyzed based on shipment volume, shipment value, quantity, and delivery delay rate.
- Delivery performance was also compared with shipment value to examine whether higher-value shipments were associated with delivery delays.

## Key Findings

- Overall delivery delay rate: **11.49%**
- Total shipments analyzed: **10,324**
- Total delayed shipments: **1,186**
- Ocean shipments had the highest delay rate among the shipment modes at **17.52%**.
- 2011 recorded the highest annual delivery delay rate at **23.83%**.
- ARV was the largest product group, accounting for **82.82%** of all shipments.

## Dashboard

The Power BI dashboard presents supply chain delivery performance across:

- Delivery delay rate by year
- Delivery delay rate by country
- Delivery delay rate by shipment mode
- Average delivery delay by shipment mode
- Delivery delay rate by fulfillment method
- Product and shipment value analysis

The dashboard includes interactive slicers for **Country, Year, and Product Group**.

## Project Structure

```text
SCMS Delivery History/
├── data/
│   └── SCMS_Delivery_History_Cleaned.csv
├── notebook/
│   └── SCMS_Delivery_History_Analysis.ipynb
├── dashboard/
│   ├── SCMS_Delivery_History.pbix
│   ├── dashboard-page-1.png
│   └── dashboard-page-2.png
└── README.md
