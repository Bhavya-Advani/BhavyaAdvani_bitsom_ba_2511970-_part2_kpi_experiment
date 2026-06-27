
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


Task 2: Define the North Star Metric
Selected North Star Metric
Trial-to-Paid Conversion Rate (converted_to_paid)
1. Why This Metric Is the Main Success Metric
The primary objective of the new onboarding and activation campaign is to increase the number of users who convert from a free trial to a paid subscription. Therefore, the Trial-to-Paid Conversion Rate is the most appropriate North Star metric because it directly measures whether the new onboarding experience successfully persuades users to become paying customers.
Unlike intermediate metrics that measure user progress or activity during onboarding, the trial-to-paid conversion rate reflects the campaign's direct contribution to business performance. It demonstrates that users have recognized sufficient value in the product to make a financial commitment, making it the clearest indicator of the campaign's overall success.
2. Why Other Metrics Are Supporting Metrics Instead
Although several other metrics are important, they measure intermediate stages of the customer journey rather than the ultimate business outcome.

Onboarding Completion Rate (completed_onboarding)
This metric measures the percentage of users who successfully complete the onboarding process. A higher completion rate indicates that the onboarding experience is intuitive and user-friendly. However, completing onboarding does not necessarily result in a paid subscription, making it a leading indicator rather than the primary success metric.

Early User Engagement (engagement_score)
Engagement measures how actively users interact with the product after onboarding. Highly engaged users are generally more likely to convert, but engagement alone does not guarantee monetization. Users may actively explore the product without deciding to purchase a subscription.

30-Day Revenue (revenue_30d)
This metric measures the financial impact generated during the first 30 days after onboarding. While it is an important business KPI, revenue is influenced by multiple factors such as subscription pricing, customer purchasing behavior, and promotional offers. As a result, it is better suited as a supporting metric for evaluating business impact rather than the primary measure of onboarding effectiveness.

Guardrail Metrics (support_tickets_30d and refund_requested)
These metrics ensure that improvements in conversion are achieved without negatively affecting customer experience or operational performance. They help identify whether increased conversions come at the cost of higher customer dissatisfaction, increased support workload, or poor-quality subscriptions.
3. How This Metric Connects to Business Growth
Improving the Trial-to-Paid Conversion Rate directly contributes to sustainable business growth by increasing the number of paying subscribers generated from the existing pool of trial users.
Higher conversion rates provide several business benefits:

Increase recurring subscription revenue.
Improve marketing efficiency by generating more paying customers from the same customer acquisition efforts.
Enhance Customer Lifetime Value (LTV) by expanding the base of paying customers who continue using the product.
Improve the LTV:CAC ratio, enabling the company to invest more confidently in future product development and customer acquisition.
Support long-term profitability through sustainable subscription growth rather than relying solely on acquiring more users.
For a subscription-based business, even modest improvements in conversion can produce significant long-term revenue gains because subscription income compounds over time.
4. Risks of Optimizing This Metric Blindly
Although the Trial-to-Paid Conversion Rate is the most important success metric, focusing exclusively on increasing conversions may lead to unintended negative consequences.

Poor User Experience
Aggressive onboarding messages or excessive pressure to subscribe may increase short-term conversions while reducing customer satisfaction and trust.

Increased Refund Requests
Users may subscribe without fully understanding the product or its value, leading to higher refund rates shortly after purchase.

Higher Customer Support Demand
If the onboarding process becomes confusing or overly complex, users may require additional assistance, increasing the number of customer support tickets.

Low-Quality Conversions
An increase in paid subscriptions is valuable only if customers remain engaged with the product. If users convert but quickly become inactive or cancel their subscriptions, the long-term business value of those conversions will be limited.

Short-Term Growth at the Expense of Long-Term Value
A campaign that increases initial conversions without improving engagement, retention, or revenue may create temporary improvements while weakening sustainable business performance.
Conclusion
The Trial-to-Paid Conversion Rate (converted_to_paid) is the most appropriate North Star metric because it directly reflects the company's primary objective of converting trial users into paying customers. However, it should not be evaluated in isolation. Leadership should assess this metric alongside supporting KPIs—such as onboarding completion, engagement, and 30-day revenue—and guardrail metrics, including support tickets and refund requests, to ensure that the new onboarding campaign delivers sustainable business growth while maintaining a positive user experience and operational efficiency. how is this
