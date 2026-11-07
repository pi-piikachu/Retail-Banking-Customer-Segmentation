
# Retail Banking Customer Segmentation & Executive Insights

**A data-driven portfolio analysis to understand customer value,
identify churn risk, and uncover cross-selling opportunities.**

![Excel](https://img.shields.io/badge/Platform-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Analytics](https://img.shields.io/badge/Focus-Customer%20Analytics-2457A6?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Portfolio%20Analysis-159B8A?style=for-the-badge)
:::

------------------------------------------------------------------------

## Overview

This project transforms retail banking customer data into an actionable
view of portfolio health. It combines data preparation, rule-based
customer segmentation, financial behaviour analysis, attrition
benchmarking, and an executive dashboard in a single Excel workbook.

The goal is not just to report what happened, but to help answer three
business questions:

1.  **Who are the most valuable customers?**
2.  **Where is customer attrition concentrated, and which groups need
    intervention?**
3.  **Where can the bank grow revenue through credit-line increases,
    card upgrades, and deeper relationships?**

## Executive snapshot

  Portfolio metric                                                      Result
  ------------------------------------------------------ ---------------------
  Customers analysed                                                **10,127**
  Overall attrition rate                                             **16.1%**
  Attrited customers                                                 **1,627**
  Average transaction amount per customer                          **\$4,404**
  Champions                                                  **1,492 (14.7%)**
  Champions + High Potential revenue share                           **71.4%**
  At Risk + Low Engagement share of attrited customers               **64.6%**
  Credit-line expansion pipeline                           **5,587 customers**

> **Key takeaway:** A relatively small group of high-value customers
> drives a disproportionate share of transaction volume, while churn is
> heavily concentrated among customers with weaker engagement. Retention
> and growth therefore need distinct, segment-specific strategies.

*Figures are taken from the workbook's analysis and management-insights
sheets. Monetary values and projected uplifts are workbook estimates,
not independently audited financial results.*

## Customer segmentation

Customers are classified into five actionable groups using behavioural
and relationship indicators, including transaction activity, transaction
value, product relationships, inactivity, and credit utilisation.

  --------------------------------------------------------------------------
  Segment                    Customers      Portfolio share Strategic
                                                            interpretation
  --------------- -------------------- -------------------- ----------------
  Champions                      1,492                14.7% High-value
                                                            customers;
                                                            prioritise
                                                            loyalty and
                                                            premium
                                                            relationship
                                                            management.

  High Potential                 3,427                33.8% Strong growth
                                                            prospects;
                                                            target relevant
                                                            credit and card
                                                            upgrades.

  Core Customers                 2,259                22.3% Established
                                                            relationships;
                                                            deepen
                                                            engagement and
                                                            cross-sell
                                                            suitable
                                                            products.

  At Risk                        2,531                25.0% Elevated
                                                            attrition risk;
                                                            prioritise
                                                            proactive
                                                            retention and
                                                            service
                                                            recovery.

  Low Engagement                   418                 4.1% Weak activity
                                                            and highest
                                                            attrition rate;
                                                            focus on
                                                            reactivation.
  --------------------------------------------------------------------------

### What the segments reveal

-   **Value concentration:** Champions and High Potential customers
    represent 48.6% of the portfolio and contribute 71.4% of transaction
    volume.
-   **Retention pressure:** At Risk and Low Engagement customers account
    for 64.6% of all attrited customers.
-   **Growth opportunity:** The workbook identifies 5,587 customers for
    potential credit-line expansion and 1,898 high-volume transactors
    for possible card-tier upgrades.

## Strategic recommendations

The management-insights section translates the analysis into three
strategic pillars.

### 1. Retention defence --- At Risk & Low Engagement

**Objective:** Reduce preventable churn and reactivate disengaged
customers.

-   Build early-warning triggers around sharp declines in transaction
    activity and prolonged inactivity.
-   Use targeted, time-bound cashback or relevant category offers to
    encourage reactivation.
-   Review complaints, contact-centre escalations, and unresolved
    service issues for high-risk customers.
-   Use coordinated app, email, and relationship-manager outreach.

**Suggested measures:** Segment-level churn rate, reactivation rate,
repeat transaction activity, and retained transaction volume.

### 2. Cross-sell acceleration --- High Potential & Core

**Objective:** Increase customer lifetime value through relevant product
expansion.

-   Offer pre-approved credit-limit reviews to eligible customers with
    suitable risk profiles.
-   Identify high-volume customers for Blue-to-Silver/Gold card upgrade
    campaigns.
-   Recommend complementary products based on existing relationship
    depth and observed behaviour.
-   Use in-app journeys and segmented email campaigns to explain the
    value of each offer.

**Workbook opportunity estimates:** Approximately 5,587 customers in the
credit-line expansion pipeline and 1,898 potential card-upgrade
candidates.

### 3. Champion retention --- Champions

**Objective:** Protect high-value relationships and reduce the impact of
losing top customers.

-   Provide priority service and dedicated relationship-management
    support.
-   Offer relevant premium benefits, loyalty rewards, and fee waivers
    tied to transparent eligibility criteria.
-   Proactively review customer needs and identify suitable wealth or
    multi-product opportunities.
-   Monitor satisfaction and service friction among high-value
    transactors.

**Suggested measures:** Champion churn, customer satisfaction/NPS,
annual transaction volume retained, and product holdings per customer.

## Workbook structure

The Excel workbook is organised into the following sheets:

  -----------------------------------------------------------------------
  Sheet                               Purpose
  ----------------------------------- -----------------------------------
  `Raw_Data`                          Original customer-level source
                                      data.

  `Clean_Data`                        Prepared dataset used for
                                      downstream analysis.

  `Segmentation`                      Customer-level behavioural scores,
                                      composite score, segment
                                      assignment, and age grouping.

  `Business_Analysis`                 Segment-level customer counts,
                                      transaction behaviour, attrition,
                                      and relationship metrics.

  `Pivot_Analysis`                    Pivot-based analysis supporting the
                                      reporting workflow.

  `Dashboard`                         Executive dashboard with headline
                                      KPIs, segment distribution,
                                      attrition comparisons, and
                                      cross-sell pipeline visuals.

  `Management_Insights`               Strategic recommendations, target
                                      KPIs, implementation priorities,
                                      ownership, and roadmap.
  -----------------------------------------------------------------------

## Dashboard highlights

The executive dashboard brings the main portfolio indicators together:

-   Total customer count and overall attrition rate.
-   Average transaction spend.
-   Segment size and portfolio concentration.
-   Attrition rate by customer segment.
-   Average transaction spend by segment.
-   Cross-selling opportunity pipeline.

The dashboard is designed for quick management review, while the
supporting sheets allow users to trace the metrics back to
customer-level and segment-level analysis.

## Methodology

The workbook follows this analytical sequence:

1.  **Data preparation:** Start with the raw customer records and use
    the prepared dataset for analysis.
2.  **Behavioural feature review:** Examine transaction amount and
    frequency, inactivity, relationship count, credit utilisation, and
    related customer attributes.
3.  **Scoring and segmentation:** Build monetary, engagement,
    relationship, and activity scores; combine them into a composite
    score and assign customer segments.
4.  **Portfolio analysis:** Aggregate customer counts, transaction
    behaviour, and attrition by segment.
5.  **Visualisation:** Present key metrics and comparisons in the
    executive dashboard.
6.  **Business translation:** Convert the findings into retention,
    cross-sell, and VIP-loyalty initiatives with proposed KPIs and
    owners.

**Important:** The segmentation in this workbook is a scoring-based
business classification. It should not be interpreted as a trained
predictive machine-learning model or as a causal explanation of churn.

## How to use

1.  Open `Retail Banking Customer Segmentation .xlsx` in Microsoft
    Excel.
2.  Start with the **Dashboard** sheet for the portfolio overview.
3.  Review **Business_Analysis** and **Segmentation** to understand
    segment-level and customer-level results.
4.  Use **Management_Insights** for the recommended interventions and
    implementation roadmap.
5.  If you modify source data, check that formulas, pivot tables, and
    dashboard outputs have refreshed correctly.

For best compatibility, open the workbook in desktop Microsoft Excel and
enable workbook calculation/refresh if prompted. Some formulas, pivot
objects, and charts may behave differently in alternative spreadsheet
applications.

## Tools & skills demonstrated

-   Microsoft Excel
-   Data cleaning and preparation
-   Formula-driven analysis
-   Customer segmentation and scoring
-   Pivot-table analysis
-   KPI design and dashboard development
-   Attrition and customer-value analysis
-   Business storytelling and strategic recommendation development

## Potential next steps

-   Validate segment definitions and scoring thresholds with business
    stakeholders.
-   Add a time-based cohort view to track changes in engagement and
    attrition.
-   Test churn prediction models against a held-out dataset and compare
    them with the current rule-based risk segmentation.
-   Measure campaign outcomes through controlled experiments rather than
    relying only on projected uplift.
-   Add refresh documentation and automated data-quality checks.

------------------------------------------------------------------------

**Turning customer data into clearer retention priorities and measurable
growth opportunities.**

