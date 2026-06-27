
# Task 1: Understand the Business Problem

## Business Problem Statement

The company has conducted an A/B test to evaluate the effectiveness of a new onboarding and activation campaign for its subscription-based digital product. Users were randomly assigned to either the **Control group**, which experienced the existing onboarding process, or the **Treatment group**, which experienced the new onboarding campaign. The purpose of this analysis is to determine whether the new campaign should be rolled out to all users by assessing its impact on user conversion, early engagement, and revenue while ensuring that it does not negatively affect user experience or operational efficiency.

### 1. Decision to Be Made

The primary objective is to determine whether the new onboarding and activation campaign (Treatment) should:

Be fully deployed to all users,
Be rejected in favor of the existing onboarding experience (Control),
Undergo additional testing to gather stronger evidence, or
Be selectively rolled out to specific user segments if the treatment performs better for certain groups.

The final recommendation should be based on both statistical evidence and business impact.

### 2. Impacted Stakeholders

The decision will directly affect several key stakeholders:
New Users:The onboarding experience influences how quickly users understand the product, complete activation, and realize value, ultimately affecting their likelihood of becoming paying customers.
Product and Growth Teams:These teams use the findings to optimize the onboarding journey, improve user activation, and increase conversion throughout the customer lifecycle.
Customer Support and Operations Teams: A more complex or confusing onboarding experience may increase customer support requests, while a smoother onboarding process can reduce operational workload.
Finance and Executive Leadership: Leadership will evaluate whether the new campaign improves customer acquisition efficiency, generates higher early revenue, increases Customer Lifetime Value (LTV), and justifies a company-wide rollout.

### 3. Target Metrics for Improvement

The campaign is designed to improve user activation, conversion, engagement, and early revenue generation.

#### Primary Success Metric (North Star Metric)

Trial-to-Paid Conversion Rate (converted_to_paid)

This is the most important business outcome because it directly reflects the campaign's ability to convert new users into paying subscribers.

#### Supporting KPI Metrics

Onboarding Completion Rate (completed_onboarding) – Measures the percentage of users who successfully complete the onboarding process.
Early User Engagement (engagement_score) – Indicates how actively users interact with the product after onboarding.
30-Day Revenue (revenue_30d)– Measures the revenue generated from users during their first 30 days and reflects the campaign's short-term financial impact.

### 4. Risks and Guardrail Metrics

While improvements in conversion and revenue are desirable, they should not come at the expense of user satisfaction or operational efficiency. The following guardrail metrics should therefore be monitored throughout the experiment:

Support Overhead (support_tickets_30d)
  An increase in customer support requests may indicate that the new onboarding experience introduces confusion, usability issues, or technical friction.

Refund Rate (refund_requested)
  A higher refund rate may suggest that the campaign attracts low-quality conversions or creates unrealistic user expectations, resulting in dissatisfaction after purchase.

Meaningful Product Adoption
  Improvements in onboarding completion should also lead to higher engagement and increased 30-day revenue. If onboarding completion increases without corresponding improvements in engagement or revenue, it may indicate that users are completing the onboarding process without realizing meaningful value from the product.

### 5. Evidence Required Before Making a Recommendation

Before recommending a full rollout, leadership requires clear evidence that the new onboarding campaign delivers measurable business value while maintaining a positive user experience.

The analysis should demonstrate:

A statistically and practically significant improvement in the primary success metric (converted_to_paid).

Positive improvements in supporting metrics, including onboarding completion, early engagement, and 30-day revenue.

No statistically significant deterioration in guardrail metrics such as support tickets or refund requests.

Funnel analysis (visited_landing_page → started_trial → completed_onboarding) to identify where users progress, where they drop off, and whether the treatment improves conversion throughout the onboarding journey.

Segment-level performance analysis to determine whether the treatment performs particularly well for specific user groups if the overall results are mixed or inconclusive.

