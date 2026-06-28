**Hypothesis Test Analysis**

**Business Objective**

The objective of this experiment is to determine whether the new onboarding experience (Treatment) increases the paid conversion rate compared to the existing onboarding experience (Control).

The business decision is whether the new onboarding flow should be launched to users.

**Metric Being Tested**

**Primary Metric:** Paid Conversion Rate

Formula:

Paid Conversion Rate = Converted Users / Total Users

**Reason for Choosing This Metric**

Paid conversion rate is the most important business metric because it directly measures how effectively users are converted into paying customers.

An increase in paid conversion rate has a direct impact on subscription growth and revenue generation.

**Hypotheses**

**Null Hypothesis (H₀)**

There is no difference in paid conversion rate between the Control and Treatment groups.

H₀: pTreatment = pControl

**Alternative Hypothesis (H₁)**

The Treatment group has a higher paid conversion rate than the Control group.

H₁: pTreatment > pControl

**Type of Test**

**One-tailed Two-Proportion Z-Test**

Reason:

The experiment aims to determine whether the Treatment performs better than the Control, not merely whether it is different.

**Significance Level**

α = 0.05 (5%)

**Test Inputs**

| **Metric**      | **Control**      | **Treatment**    |
| --------------- | ---------------- | ---------------- |
| Total Users     | 690              | 710              |
| Converted Users | \[Insert Count\] | \[Insert Count\] |
| Conversion Rate | \[Insert Rate\]  | \[Insert Rate\]  |

**Test Output**

P-value: \[Insert P-value\]

Test Statistic (Z-score): \[Insert Z-score\]

**Decision Rule**

If P-value < 0.05:

Reject the Null Hypothesis.

If P-value ≥ 0.05:

Fail to Reject the Null Hypothesis.

**Interpretation Logic**

A statistically significant result indicates that the observed improvement in paid conversion rate is unlikely to be due to random chance.

If the null hypothesis is rejected, there is sufficient evidence to conclude that the Treatment improves paid conversion performance.

**Business Interpretation**

The experiment evaluates whether the new onboarding experience should be launched.

If the Treatment demonstrates a statistically significant increase in paid conversion rate while maintaining acceptable guardrail metrics, the business should consider rolling out the Treatment.

The final decision should not rely solely on conversion improvement and must also account for refund rate, support ticket rate, engagement, and conversion quality.

Task 8

**Guardrail Metric Evaluation**

The decision to launch the Treatment should not be based solely on conversion improvement. Several guardrail metrics were evaluated to assess potential risks.

**1\. Refund Rate**

Purpose:

Measures whether users who convert are satisfied with the product and continue their subscription.

Risk Assessment:

A higher refund rate may indicate that users are converting without fully understanding the offering or that expectations are not being met.

Conclusion:

The refund rate should remain stable after rollout. Significant increases would be a warning sign.

**2\. Support Ticket Rate**

Purpose:

Measures operational burden and user friction.

Risk Assessment:

An increase in support tickets may suggest confusion during onboarding or difficulties using the product.

Conclusion:

If support ticket rates increase substantially, additional onboarding improvements may be required before full rollout.

**3\. Average Days to Convert**

Purpose:

Measures how quickly users become paying customers.

Risk Assessment:

Longer conversion times may reduce revenue velocity and indicate a less efficient customer journey.

Conclusion:

A decrease in average days to convert is a positive signal because users reach the payment stage more quickly.

**4\. Engagement Score**

Purpose:

Measures user interaction and product adoption.

Risk Assessment:

A conversion increase accompanied by declining engagement may indicate low-quality conversions.

Conclusion:

Higher engagement alongside higher conversion suggests stronger user interest and healthier long-term retention potential.

**5\. Segment-Level Performance**

Purpose:

Ensures the Treatment performs consistently across different user groups.

Segments Evaluated:

- Region
- Device Type
- Traffic Source

Risk Assessment:

If a segment experiences declining performance while the overall average improves, a full rollout may negatively impact that segment.

Conclusion:

Segment-level results should be reviewed before a complete launch decision is made.

**Overall Guardrail Assessment**

The Treatment should only be launched if:

- Conversion rate improves significantly.
- Refund rate remains acceptable.
- Support ticket volume remains manageable.
- Engagement does not decline.
- No major segment experiences severe performance deterioration.

These metrics help ensure that conversion gains are sustainable and do not create long-term business risks.