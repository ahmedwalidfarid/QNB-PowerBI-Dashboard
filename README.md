# Banking Analytics Dashboard | Power BI

## 1. Project Overview

An end-to-end Business Intelligence project developed using Microsoft Power BI to analyze banking performance, customer behavior, financial activities, and service utilization.

The objective was not simply to visualize available data, but to transform banking data into meaningful business insights by identifying performance indicators, investigating customer patterns, comparing financial activities, and translating analytical findings into potential business actions.

The dashboard follows a management-oriented analytical approach, where each KPI and visualization serves a specific analytical purpose.

**Project inspiration:** QNB corporate visual identity  
**Dataset:** Fictional banking dataset  
**Project type:** Independent educational and portfolio project

## 2. Business Questions

The analysis was structured around six major business questions:

1. **Overall Performance:** How is the bank performing in terms of customer base, financial balances, lending activities, and transaction volume?
2. **Customer Relationships:** How effectively are customers adopting banking services, and how does financial contribution differ across customer segments?
3. **Loan Portfolio:** How are loans distributed, and what differences exist between active and completed loans?
4. **Transaction Behavior:** How does transaction activity vary over time, across seasons, transaction types, and customer segments?
5. **Geographical Performance:** How is transaction value distributed across different states?
6. **Service Effectiveness:** How effectively are customer support requests being resolved?

## 3. Analytical Decisions & KPI Selection

KPIs were selected according to the business questions they help answer, rather than simply displaying every available numerical field.

### Executive Overview

The executive page combines operational and financial indicators to provide management with a consolidated view of banking performance.

| KPI | Analytical Purpose |
|---|---|
| Total Customers | Measure the size of the customer base. |
| Total Accounts | Monitor banking account adoption and scale. |
| Total Cards | Evaluate the scale of card services. |
| Total Loans | Monitor lending portfolio volume. |
| Total Transactions | Measure transaction activity. |
| Total Balance | Evaluate the financial balance held across accounts. |
| Total Transaction Amount | Quantify overall transaction value. |
| Total Loan Amount | Measure the size of the lending portfolio. |
| Total Loan Payback | Monitor the value of loan repayments. |
| Average Interest Rate | Understand the interest-rate profile of the loan portfolio. |

**Analytical reasoning:** Customer counts alone cannot describe banking performance. Combining customer, account, lending, and financial indicators provides a broader perspective on operational scale and financial activity.

### Customers & Accounts Analysis

This section investigates customer distribution, account adoption, and differences in financial contribution.

Key measures include:

- Customers With Accounts and Customers Without Accounts.
- Average Balance per Customer.
- Customer segmentation based on financial balance.
- Account distribution across states.
- Customer cohort analysis by joining year.

**Analytical reasoning:**

- Comparing customers with and without accounts helps identify potential opportunities to improve service adoption.
- Average Balance per Customer provides a normalized measure that complements total balance.
- Customer segmentation helps investigate differences in financial contribution between customer groups.
- Cohort analysis helps examine customer acquisition patterns across different joining periods.

### Loan Portfolio Analysis

This section examines lending activities and repayment performance.

Key measures include:

- Active Loans and Completed Loans.
- Average Loan Duration.
- Maximum and Minimum Loan Amount.
- Loan distribution by type.
- Loan amounts across customer segments.
- Loan repayment patterns.

**Analytical reasoning:**

Loan volume alone does not provide enough information about portfolio performance. Comparing active and completed loans provides additional context about repayment progress.

Loan status is derived using the available loan date fields rather than relying on a predefined status column.

An important business recommendation derived from the analysis is to prioritize repayment-support initiatives for D Class customers and investigate the practices associated with A Class's higher completion rate.

### Transaction Analysis

This section investigates transaction activity from multiple perspectives.

Key measures include:

- Total Transaction Amount.
- Average Transaction Amount.
- Average Transactions per Account.
- Maximum and Minimum Transaction.
- Monthly transaction trends.
- Seasonal performance.
- Transaction type distribution.
- Transaction behavior across customer segments.

**Analytical reasoning:**

Total transaction value and average transaction value answer different questions.

Total value measures overall financial activity, whereas average value provides additional insight into the typical transaction size.

Monthly and seasonal analysis adds a time dimension, helping identify changes in activity that may require further investigation.

### Geographical Transaction Analysis

This section compares transaction contributions across different states.

The analysis uses state-level transaction value comparisons to investigate geographical concentration and identify areas contributing significantly to overall transaction activity.

**Analytical reasoning:**

Geographical comparisons help management understand where transaction activity is concentrated. However, higher transaction value should not automatically be interpreted as stronger customer engagement or profitability.

 Cards & Customer Support Analysis

This section investigates card services and customer support effectiveness.

Key measures include:

- Card-related activity.
- Total Support Calls.
- Solved Calls.
- Unsolved Calls.
- Resolution Rate.

Analytical reasoning:

The number of support calls alone does not indicate service effectiveness.

Separating solved and unsolved requests and monitoring resolution rate provides a more meaningful perspective on the bank's ability to address customer issues.

 4. Business Recommendations

The analysis supports several potential business actions:

| Area | Recommendation |
|---|---|
| Loan Repayment | Prioritize repayment-support initiatives for D Class customers. |
| Loan Performance | Investigate the practices associated with A Class's higher completion rate. |
| Customer Adoption | Investigate differences in account adoption across customer groups and geographical areas. |
| Transaction Activity | Use monthly and seasonal patterns to support operational planning. |
| Customer Support | Monitor resolution performance to identify opportunities to improve customer service. |

These recommendations are based on descriptive analysis and should be investigated further before implementing operational changes.


 5. Dashboard Structure
The report consists of eight pages:
1. Home Page
2. Executive Overview
3. Customers
4. Loans
5. Transactions
6. States of Transactions Share
7. Banking Services
8. Recommendations
Each page addresses a specific analytical area while contributing to an integrated view of banking operations.

 6. Project Limitations
- The dataset is fictional and does not represent actual banking operations.
- The analysis is descriptive and does not establish causal relationships.
- Customer segments represent analytical groupings rather than officially defined banking classifications.
- Business recommendations require additional validation before real-world implementation.
  
 7. Disclaimer
This project is an independent educational and portfolio project using a fictional banking dataset.
Its visual identity is inspired by QNB, but the project is not affiliated with, endorsed by, or based on actual operational data from QNB.



Primary Technology:Microsoft Power BI  
Domain:Banking & Financial Analytics  
Focus:Business Intelligence, Customer Analytics, Financial Performance, and Decision Support
