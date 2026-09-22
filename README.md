# NIFTY 50 Futures Market Analysis
**Prepared by:** Tushar Narendra Varkhede

## Market Activity, Basis Behaviour & Open Interest Analysis of NIFTY 50 Index Futures

**Analysis Period:** 01-Jan-2025 to 31-Dec-2025

## Project Overview

This project analyzes NIFTY 50 index futures across the 2025 calendar year, focusing on:

- Contract volume and market activity
- Futures basis and basis percentage (cost-of-carry behaviour)
- Open interest rollover between near, next and far month contracts
- Price–open interest interpretation (buildup/unwinding classification)
- Monthly and expiry-wise trends
- Dashboard-based reporting of key metrics

## Key Areas Covered

1. Executive Summary
2. Scope and Approach
3. Findings
4. Dashboard
5. Summary
6. Monthly Summary
7. Expiry Summary
8. Basis Analysis
9. OI Interpretation Summary
10. Conclusion

## Tools Used

- Microsoft Excel
- Data cleaning and preparation
- Futures basis analysis
- Open interest interpretation
- Monthly and expiry-wise analysis
- Excel formulas and pivot-style summaries
- Dashboard development

## Important Limitations

- Options data is not included; this is a futures-only study.
- No interest-rate or dividend data was supplied, so the implied carry rate is not benchmarked against a market rate.
- 8 records are no-trade rows and are excluded from averages.
- 15 records have prices but no underlying index value, so basis could not be computed for those rows.
- 24 records could not be classified for price–OI direction (first row of an expiry series, blank rows, and the row after a blank).
- The source file was cleaned (exact duplicates removed) but was not reconciled directly against NSE.
- The signal test on price–OI labels rests on small samples (25–67 observations per label) and should not be read as a tradable edge.

## Files Included

- `Project_2_NIFTY_Futures_Analysis_2025_Completed.xlsx` — Excel workbook containing the analysis and dashboard.
- `Project_2_NIFTY_Futures_Analysis_2025_Completed_FINAL.pdf` — Detailed project report.

## Disclaimer

This project is prepared for educational, analytical, and portfolio purposes only. The analysis is not investment advice, a trading recommendation, or a guarantee of future market performance.

