**Task 1**

The company must decide whether to roll out the new onboarding and activation campaign to all users. This decision impacts every new user entering the product funnel. The primary metric that must improve is **Paid Conversion Rate** (converted to paid). Risks to monitor include refund rate, support ticket volume, and engagement quality. A statistically significant improvement in conversion with no degradation in guardrail metrics is required before recommending a full launch.

**Task 2 -**

**Selected North Star Metric: Paid Conversion Rate**

_(converted_to_paid column - % of users who converted from trial to paid)_

**Why this is the North Star metric:**

Paid Conversion Rate is the single metric that confirms a user experienced enough value to make a financial commitment. Every other metric in this experiment - landing page visits, trial starts, onboarding completions, engagement scores - is a leading indicator. None of them generate revenue except this metric.In a subscription business, conversion is the moment the unit economics begin. It is the bridge between acquisition cost and lifetime value.

A campaign can inflate conversion rate through urgency tactics, misleading promises, or targeting easy-to-convert but low-LTV users. If leadership only watches conversion rate, they may scale a campaign that is quietly destroying revenue quality and overloading the support team. This is why guardrail metrics must be evaluated alongside the North Star before any launch decision.

**Why other metrics are supporting metrics, not the North Star:**

| **Metric**            | **Why it's supporting, not North Star**                                                                                                                                            |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| visited_landing_page- | Measures reach, not value. A user can visit and immediately leave                                                                                                                  |
| started_trial-        | Measures curiosity, not commitment. Trial ≠ revenue                                                                                                                                |
| completed_onboarding- | Measures activation, not monetization. A user can complete onboarding and never pay                                                                                                |
| revenue               | Looks similar across groups (\$51.75 vs \$53.88) - misleading because it's dragged down by non-converters. Revenue per converter is actually LOWER in Treatment (\$770 vs \$1,630) |
| engagement_score      | Strong predictor of conversion but not the outcome itself. Engagement without conversion = no business value                                                                       |

**How Paid Conversion Rate connects to business growth:**

In a subscription model, every percentage point of conversion rate improvement compounds across the entire user base. If 10,000 users sign up monthly:

- At 3.17% conversion → 317 paying users
- At 6.99% conversion → 699 paying users
- That is **382 additional paying users per month** from the same acquisition spend

This directly increases Monthly Recurring Revenue (MRR) without increasing Customer Acquisition Cost (CAC). It improves the CAC:LTV ratio, which is the core health metric of any subscription business.

**What could go wrong if this metric is optimized blindly:**

This dataset itself is the warning. Treatment doubled conversion but also:

- Increased support tickets by **+70%** (21.9% → 37.2%) - suggesting users are confused or misled
- Dropped revenue per converter from **\$1,630 to \$770** - Treatment is attracting lower-value converters
- Introduced refund requests (0% → 0.42%) that did not exist in Control

A campaign can inflate conversion rate through urgency tactics, misleading promises, or targeting easy-to-convert but low-LTV users. If leadership only watches conversion rate, they may scale a campaign that is quietly destroying revenue quality and overloading the support team. This is why guardrail metrics must be evaluated alongside the North Star before any launch decision.

**Task 3**

**North Star**

- Paid Conversion Rate - % of all users who convert to a paid subscription within the experiment window

**Primary Driver 1 - Funnel Progression**  
Measures how effectively users move through the top of the funnel before reaching the conversion decision.

- Sub-driver 1: **Landing Page Visit Rate** - are users even reaching the product? (Control 63.6% vs Treatment 72.6%)
- Sub-driver 2: **Trial Start Rate** - of those who visit, how many engage enough to start a trial? (Control 25.1% vs Treatment 29.1%)

**Primary Driver 2 - Activation Quality**  
Measures whether users are genuinely understanding and experiencing the product's value.

- Sub-driver 1: **Onboarding Completion Rate** - users who finish onboarding are far more likely to convert (Control 15.6% vs Treatment 21.3%)
- Sub-driver 2: **Engagement Score** - a continuous 0-100 score reflecting in-product activity depth (Control avg 57.0 vs Treatment avg 62.9)

**Primary Driver 3 - Revenue & Retention**  
Measures the quality and speed of conversion, not just whether it happens.

- Sub-driver 1: **Revenue per Converter** - average revenue_30d among converted users only. Critical because Treatment shows LOWER revenue per converter (\$770 vs \$1,630) despite higher conversion volume
- Sub-driver 2: **Days to Convert** - speed of conversion signals campaign urgency effectiveness and user intent quality

**Guardrail 1 - Support Ticket Rate**  
support_tickets_30d - THIS IS THE BIGGEST RED FLAG IN YOUR DATA. Treatment = 37.2% vs Control = 21.9%. A 70% increase. Must be investigated before full launch. Write this prominently.

**Guardrail 2 - Refund Rate**  
refund_requested - Control had zero refunds. Treatment shows 0.42%. Small in absolute terms but directionally concerning. Suggests some Treatment converters regretted their purchase.

**Guardrail 3 - Revenue per Converter**  
Also doubles as a guardrail. Treatment brought in more converters but each one is worth less than half of a Control converter. If this pattern holds at scale, revenue growth will disappoint despite strong conversion numbers.