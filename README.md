# Bank Marketing Campaign Effectiveness & Customer Conversion Analytics

## Project Overview

This project analyzes a bank's direct marketing campaign data to understand customer subscription behavior and evaluate campaign effectiveness.

Using Microsoft Excel, I analyzed customer demographics, financial characteristics, campaign contact patterns, and previous campaign outcomes to identify factors associated with term deposit subscriptions.

The goal was to translate historical campaign data into practical business insights that could support more informed marketing decisions.

## Business Problem

The bank needs to understand:

- Which customer segments have higher subscription rates?
- How do contact frequency and previous campaign outcomes relate to conversion?
- Does campaign timing show differences in subscription rates?
- What opportunities exist to improve customer targeting and campaign efficiency?

## Dataset

- **Source:** UCI Machine Learning Repository — Bank Marketing
- **Records:** 45,211
- **Features:** 17
- **Target variable:** `y` — whether the customer subscribed to a term deposit
- **Outcome categories:** Yes / No

## Tools & Techniques

**Tool:** Microsoft Excel

- Data cleaning and validation
- Duplicate record checks
- PivotTables and summary analysis
- Excel formulas and calculated metrics
- Customer segmentation
- Conversion-rate analysis
- Charts and dashboard development

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Customers | 45,211 |
| Successful Subscriptions | 5,289 |
| Overall Conversion Rate | 11.70% |
| Exact Duplicate Records | 0 |

## Key Findings

### 1. Customer Demographics
- Customers aged 60 and above had a subscription rate of 33.63%.
- Students had a subscription rate of 28.68%.
- Customer segments showed meaningful differences in historical conversion rates.

### 2. Financial Characteristics
- Customers without housing loans had a 16.70% subscription rate, compared with 7.70% for customers with housing loans.
- Customers without personal loans had a 12.66% subscription rate, compared with 6.68% for customers with personal loans.

### 3. Campaign Contact Frequency
- Customers contacted once had a 14.60% subscription rate.
- Customers contacted 11 or more times had a 3.93% subscription rate.
- Higher contact frequency was associated with lower conversion rates in this dataset.

### 4. Previous Campaign Outcomes
- Customers with a successful previous campaign outcome had a 64.73% subscription rate.
- Customers with a previous failed outcome had a 12.61% subscription rate.

### 5. Campaign Timing
- March showed the highest subscription rate at 51.99%, based on 477 customers.
- May had the lowest rate at 6.72%.
- Results for months with smaller customer groups should be interpreted cautiously.

### 6. Call Duration
- Calls lasting more than five minutes had a 28.17% subscription rate.
- Calls lasting less than one minute had a 0.19% subscription rate.
- Call duration is known after a call takes place, so it should not be treated as a pre-campaign targeting variable.

## Business Recommendations

Based on the historical analysis:

1. **Refine customer segmentation:** Evaluate targeted outreach strategies for customer groups with higher historical subscription rates.
2. **Use previous campaign outcomes:** Consider previous campaign success when prioritizing future customer engagement.
3. **Review contact frequency:** Assess whether repeated contact strategies are efficient and whether contact limits should be tested.
4. **Evaluate campaign timing:** Investigate seasonal patterns further using additional campaign data before making scheduling decisions.
5. **Improve data completeness:** Review missing or unknown values in contact and previous campaign outcome fields to improve future analysis.

## Excel Dashboard

The interactive-style Excel dashboard summarizes the analysis through:

- Three KPI cards: total customers, successful subscriptions, and overall conversion rate.
- Five visualizations covering age group, job category, campaign month, contact frequency, and previous campaign outcome.
- A key business insights section highlighting major findings.
- A separate dashboard data worksheet supporting the visualizations.

## Project Deliverable

`Bank_Marketing_Campaign_Analytics.xlsx`

The workbook contains the cleaned dataset, data quality checks, subscription summaries, exploratory analysis, dashboard, and supporting dashboard data.

## Limitations

The findings represent historical associations and do not establish causation. Some customer segments and campaign months have smaller sample sizes, which can make their conversion rates more volatile.

Call duration is a post-call measure and should not be used as a pre-call targeting input. Further testing would be required before implementing campaign changes.

## Conclusion

This project demonstrates how Excel can be used to transform raw marketing data into structured analysis, customer segmentation, campaign performance insights, and practical business recommendations.
