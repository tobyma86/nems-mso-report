# Navigating the Numbers: Insights into Insurance Claim Management

## Summary

This report delineates the classification of insurance claim entries, and analyzes the data for the Managed Service Organization (MSO) at North East Medical Services (NEMS). Central to this analysis is a payment summary table derived from NEMS's medical management database, which encompasses individual insurance claim summaries from various providers to HPSM from July 2024 to March 2025. Each entry incorporates key data fields, and the raw dataset has been omitted to ensure HIPAA compliance. The analysis highlights critical areas for strategic improvement, including a high prevalence of "Balance Due" claims, significant seasonal fluctuations, and data inconsistencies.

## Key Findings
### Financial Strain from Outstanding Balances
A substantial financial constraint was identified, with over 68% of claims (279 out of 409 records) classified as "Balance Due". This indicates potential issues with patient financial responsibility, initial claim submission accuracy, or the efficiency of billing and collection processes.

### Time-Series Dynamics and Surges
* A significant surge in claim volume occurred in December 2024, with 216 claims, possibly due to a major billing cycle culmination or a year-end push to finalize collections.
* Conversely, March 2025 showed an unprecedented cumulative outstanding balance of $11,268, suggesting a potential bottleneck in payment resolution for that period.
* Several months (July-August 2024 and January-March 2025) had a ```TOTAL_PAID``` value of zero while maintaining high balances, indicating a severe bottleneck where claims are processed but payments are not being recorded.

### Data Peculiarities
The ```TRUE_BILL_AMT```, ```TOTAL_PAID```, and ```BALANCE``` columns showed a limited number of discrete values, suggesting a tiered service model or predefined payment scenarios.

---
## Repository Structure

```
.
├── README.md                               # Project documentation
├── report (NEMS volunteering).pdf          # Report


```

---
