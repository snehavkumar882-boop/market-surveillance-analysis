# Market Surveillance & Financial Trading Analytics

## Project Overview

An Excel-based financial data analytics project designed to identify unusual stock trading activity using simulated market data. The project applies rolling average calculations, volume-ratio analysis and rule-based alert logic to identify trading observations requiring further investigation.

The project is planned to be extended with an interactive Power BI dashboard.

## Objectives

- Analyse stock trading volume and closing prices.
- Calculate rolling five-day average trading volume.
- Identify unusual volume spikes using predefined thresholds.
- Monitor daily stock price movements.
- Visualise trading patterns and surveillance alerts.
- Extend the analysis into interactive business intelligence reporting.

## Tools & Technologies

### Implemented
- Microsoft Excel
- AVERAGE and IF functions
- Rolling averages and volume ratios
- Percentage price-change calculations
- Rule-based alert logic
- Excel charts and data visualisation

### Planned
- Microsoft Power BI
- DAX measures
- Interactive dashboard
- KPI cards and alert-status reporting

## Dataset

The project uses simulated stock trading data covering 15 trading days for one stock.

The dataset includes:
- Trading dates
- Stock identifier
- Closing prices
- Trading volumes

## Methodology

1. Prepared and organised simulated trading data.
2. Calculated the average trading volume over the previous five trading days.
3. Compared current trading volume against the rolling average.
4. Applied a threshold-based alert rule: trading volume at least 2× the previous five-day average is classified as REVIEW.
5. Used daily price movements as supporting analytical information.
6. Created Excel charts to visualise trading activity.

## Key Findings

The analysis identifies unusual trading-volume observations that exceed the predefined threshold and flags them for further investigation.

The initial five trading observations establish the rolling baseline; the remaining ten observations are eligible for evaluation.

## Planned Power BI Enhancements

- Import the processed Excel dataset into Power BI.
- Create DAX measures for trading volume, average volume and alert counts.
- Develop interactive KPI cards.
- Visualise price and volume trends.
- Add filters for dates and surveillance status.
- Build an interactive market surveillance dashboard.

## Limitations

This is an educational prototype based on simulated data. A REVIEW flag indicates unusual trading volume only; it does not establish insider trading, market manipulation or any regulatory violation.

The alert logic is threshold-based and requires further validation using real-world financial market data.

## Future Improvements

- Integrate real historical stock-market datasets.
- Expand analysis across multiple stocks.
- Introduce statistical anomaly detection techniques.
- Develop a complete Power BI reporting dashboard.
- Explore machine learning approaches for identifying unusual trading patterns.
