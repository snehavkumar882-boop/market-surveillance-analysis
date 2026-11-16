# Market Surveillance & Financial Trading Analytics Dashboard

## Project Overview

A financial data analytics project designed to identify unusual stock trading activity using simulated market data. The project combines Microsoft Excel and Power BI to analyse trading volumes, monitor price movements, identify unusual patterns and visualise surveillance alerts.

## Objectives
- Analyse stock trading volume and closing prices.
- Calculate rolling five-day average trading volume.
- Identify unusual volume spikes using predefined thresholds.
- Monitor daily stock price movements.
- Develop interactive financial analytics dashboards.
- Present surveillance insights through KPI indicators and visual reports.

## Tools & Technologies
- Microsoft Excel
- Microsoft Power BI
- DAX (Data Analysis Expressions)
- AVERAGE and IF functions
- Rolling averages and volume ratios
- Percentage price-change calculations
- Rule-based alert logic
- Data modelling and visualisation

## Dataset

Simulated stock trading data covering 15 trading days for one stock, including:
- Trading dates
- Stock identifier
- Closing prices
- Trading volumes

## Methodology
1. Prepared and organised simulated trading data in Excel.
2. Calculated rolling five-day average trading volume.
3. Computed volume ratios and daily percentage price changes.
4. Applied threshold-based alert logic to flag trading volume at least 2× the previous five-day average.
5. Imported the processed dataset into Power BI.
6. Developed DAX measures for key trading metrics and alert counts.
7. Created interactive dashboards with KPI cards, volume trends, price movements and surveillance classifications.

## Key Findings

Identified unusual trading-volume observations exceeding the predefined threshold and classified them for further investigation.

The first five observations establish the rolling baseline, while the remaining ten observations are eligible for evaluation.

## Power BI Dashboard

The dashboard presents:
- Total trading days
- Average trading volume
- Unusual activity alerts
- Normal versus review classifications
- Trading volume trends
- Stock price movements
- Interactive date and alert-status filters

## Limitations

This is an educational prototype based on simulated data. A REVIEW flag indicates unusual trading volume only; it does not establish insider trading, market manipulation or regulatory violations.

The alert logic is threshold-based and requires further validation using real-world financial market data.

## Future Improvements
- Integrate real historical stock-market datasets.
- Expand analysis across multiple stocks.
- Introduce statistical anomaly detection techniques.
- Explore machine learning approaches for identifying unusual trading patterns.
