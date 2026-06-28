# A/B Testing Experiment Analysis

## Project Overview

This project analyzes the impact of a new onboarding experience (Treatment) compared to the existing onboarding flow (Control) using A/B testing methodology.

The objective is to determine whether the Treatment improves business performance, particularly paid user conversions, while monitoring key guardrail metrics to ensure overall user experience and business health are maintained.

---

## Business Objective

Evaluate whether the new onboarding experience should be launched by measuring its effect on user conversion and engagement metrics.

---
```

---

## Data Cleaning

The dataset was reviewed and cleaned before analysis.

Cleaning activities included:

* Removal of duplicate user records
* Validation of experiment group assignments
* Review of missing values
* Verification of metric consistency

Final dataset used for analysis:

* Control Group: 690 users
* Treatment Group: 710 users

---

## Experiment Metrics

The following metrics were evaluated:

* User Count
* Landing Page Visit Rate
* Trial Start Rate
* Onboarding Completion Rate
* Paid Conversion Rate
* Average Revenue Per User (ARPU)
* Average Revenue Per Converted User
* Refund Rate
* Support Ticket Rate
* Average Engagement Score
* Average Days to Convert

Segment-level analysis was also performed across:

* Region
* Device Type
* Traffic Source

---

## Hypothesis Testing

### Null Hypothesis (H₀)

There is no difference in paid conversion rate between the Control and Treatment groups.

### Alternative Hypothesis (H₁)

The Treatment group has a higher paid conversion rate than the Control group.

### Test Type

One-Tailed Two-Proportion Z-Test

### Significance Level

α = 0.05

---

## Key Results

| Metric          | Control | Treatment |
| --------------- | ------- | --------- |
| Users           | 690     | 710       |
| Converted Users | 22      | 50        |
| Conversion Rate | 3.19%   | 7.04%     |

### Statistical Output

* Z-Score: 3.29
* P-Value: 0.0005
* Decision: Reject Null Hypothesis

The results indicate that the Treatment significantly improved paid conversion rate.

---

## Guardrail Metrics Evaluated

The following guardrail metrics were reviewed to ensure conversion gains did not introduce business risks:

* Refund Rate
* Support Ticket Rate
* Average Days to Convert
* Engagement Score
* Segment-Level Performance

---

## Recommendation

The Treatment demonstrated a statistically significant improvement in paid conversion rate and should be considered for rollout.

However, guardrail metrics and segment-level performance should continue to be monitored to ensure sustainable long-term results.

---

## Tools Used

* Microsoft Excel
* Pivot Tables
* Descriptive Analysis
* Two-Proportion Z-Test
* A/B Testing Framework

---
