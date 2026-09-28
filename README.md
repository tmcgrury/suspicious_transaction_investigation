# Suspicious Transaction Investigation

An Excel-based fraud risk case study using **synthetic transaction data**. I compared a customer's activity from September 1–3, 2026 with historical behavior, built an investigation dashboard, and documented a recommendation for further review.

## Case question

Does the recent activity for Customer C104 differ enough from their historical pattern to warrant investigation?

## What I analyzed

- Transaction amount and frequency against historical baselines
- Changes in device IDs and transaction locations
- Multiple risk indicators together, rather than treating any one signal as proof of fraud

## Key findings

| Measure | Historical activity | Review period |
| --- | ---: | ---: |
| Average transaction amount | $115.15 | $1,437.21 |
| Transactions per day | 0.36 | 2.33 |
| States observed | 1 | 3 |
| Device IDs observed | 1 | 3 |

Seven transactions totaling **$10,060.49** were marked for review over the three-day period. The average transaction amount rose by about **1,148%**, while transaction frequency rose by about **553%**.

## Assessment

The combined changes in spending, frequency, location, and devices warrant further investigation. These indicators **do not establish that fraud occurred**. I recommended verifying the activity with the customer and reviewing the additional devices, locations, and transaction history before deciding whether to escalate.

## Tools and deliverables

- **Microsoft Excel:** historical comparisons, transaction analysis, risk flags, and an investigation dashboard
- **Canva:** a concise case study presenting the evidence, assessment, and recommended next steps

[View the case study (PDF)](./Suspicious_Transaction_Investigation.pdf)

## About the data

This is a portfolio exercise using synthetic data. Customer C104 is a case identifier in the fictional dataset; no real customer information is represented.

---

**Tanya McGrury** · [LinkedIn](https://www.linkedin.com/in/tanyamcgrury/)
