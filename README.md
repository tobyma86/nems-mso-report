# Navigating the Numbers: Insights into Insurance Claim Management

## Summary

This report delineates the classification of insurance claim entries, and analyzes the data for the Managed Service Organization (MSO) at North East Medical Services (NEMS). Central to this analysis is a payment summary table derived from NEMS's medical management database, which encompasses individual insurance claim summaries from various providers to HPSM from July 2024 to March 2025. Each entry incorporates key data fields, and the raw dataset has been omitted to ensure HIPAA compliance. The analysis highlights critical areas for strategic improvement, including a high prevalence of "Balance Due" claims, significant seasonal fluctuations, and data inconsistencies.

## Key Findings
### Financial Strain from Outstanding Balances
A substantial financial constraint was identified, with over 68% of claims classified as "Balance Due", indicating potential issues with patient financial responsibility, initial claim submission accuracy, or the efficiency of billing and collection processes. Addressing this is crucial for the organization's financial stability and revenue flow.

### Time-Series Dynamics and Surges
The report identifies a major surge in claim volume in December 2024, which could be due to a year-end push to finalize collections or patient behavior influenced by holiday seasons; it also demonstrates the high outstanding balance in March 2025, which suggests a bottleneck in payment resolution. Additionally, several months had a ```TOTAL_PAID``` value of zero with high balances, indicating a severe bottleneck where payments are not being recorded.

### Data Inconsistencies
The report notes that columns like ```TRUE_BILL_AMT```, ```TOTAL_PAID```, and ```BALANCE``` show a limited number of discrete values, which could suggest a tiered service model or predefined payment scenarios. The presence of "DUP" (duplicate) and "Needs manual review" entries, while small, highlights potential data collection issues or system errors that need to be addressed to improve data accuracy and reliability.

---
## Repository Structure

```
.
├── README.md                               # Project summary and documentation
├── report (NEMS volunteering).pdf          # Report


```

---
