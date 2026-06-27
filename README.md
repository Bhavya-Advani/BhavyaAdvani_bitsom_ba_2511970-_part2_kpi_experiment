
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
The Trial-to-Paid Conversion Rate (converted_to_paid) is the most appropriate North Star metric because it directly reflects the company's primary objective of converting trial users into paying customers. However, it should not be evaluated in isolation. Leadership should assess this metric alongside supporting KPIs—such as onboarding completion, engagement, and 30-day revenue—and guardrail metrics, including support tickets and refund requests, to ensure that the new onboarding campaign delivers sustainable business growth while maintaining a positive user experience and operational efficiency.


Experiment analysis approach

Parameter	Validation Metric / Finding	Strategic Action Taken
**Duplicate User IDs:**	8 duplicate rows detected (e.g., USR-100096, USR-100433). Exact row clones.	Deduplicated by keeping the first occurrence.
**Group Counts	Control:** 693 users ; Treatment: 715 users (Pre-deduplication).	Sample sizes are balanced enough for standard statistical tests.
**Missing Values:**	device_type (18), traffic_source (24), engagement_score (14), days_to_convert (1336).	Categorical: Labeled as 'Unknown'. Scores: Imputed via median. Days to convert: Left blank for non-converters.
**Invalid Binary Flags:**	Checked all columns: All strictly map to [0, 1].	No clean-up required.
**Revenue Outliers:**	Max revenue reached $8,610.72. Out of 72 paid conversions, 7 generated over $2,000.	Real commercial outliers. Kept intact for revenue-metric tracking, winsorized version prepared for T-tests.
**Segment Alignment	Category**: distributions remain symmetric across groups.	No randomization bias detected. Funnel ready for analysis.



		Metric	Control Group	Treatment Group	Absolute Shift / Observations
User Count:	690; 710;	Well-balanced; random cell assignment.
Landing Page Visit Rate:	63.60%;	72.40%;	+8.8%; lift in top-of-funnel activity.
Trial Start Rate:	25.10%;	29.00%;	+3.9%; conversion into evaluation period.
Onboarding Completion Rate:	15.70%;	21.10%;	+5.4%; walkthrough clearance rate.
Paid Conversion Rate (North Star):	3.20%;	7.00%;	+3.8%; absolute lift (more than doubled).
Average Revenue Per User (ARPU):	$51.97;	$54.25;	Slight growth (+4.4%); but heavily compressed.
Avg Revenue Per Converted User:	$1,630.10;	$770.41;	Dropped by 52.7% (Indicates low-value subscriptions).
Refund Rate (Guardrail):	0.00%;	0.42%;	Small uptick in the treatment variant.
Support Ticket Rate (Guardrail):	14.80%;	24.80%;	+10.0%; spike (Severe post-launch UX confusion).
Average Engagement Score:	57;	62.9;	Improved active interaction marks.
Average Days to Convert:	8.9 Days;	6.4 Days;	-2.5 Days; faster time-to-value (TTV).



# Task 8: Evaluation of Guardrail Metrics

## Objective

Although the Treatment group achieved a statistically significant improvement in the Trial-to-Paid Conversion Rate (North Star Metric), the rollout decision should not rely solely on conversion performance. Guardrail metrics were evaluated to determine whether the increased conversion was achieved without negatively affecting customer experience, operational efficiency, or revenue quality.



| **Guardrail Metric**                   | **Control** | **Treatment** | **Evaluation**                                                                                                                                                                                                                                                                                                          | **Risk Assessment**      |
| -------------------------------------- | ----------: | ------------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------ |
| **Refund Rate**                        |       0.00% |         0.42% | The Treatment group recorded a small increase in refund requests. Although the increase is relatively modest, it may indicate that some newly converted users were dissatisfied or that the onboarding experience created expectations that were not fully met.                                                         | **Low to Moderate Risk** |
| **Support Ticket Rate**                |      14.80% |        24.80% | Support ticket volume increased by **10 percentage points** following the introduction of the new onboarding campaign. This suggests that users may have experienced greater confusion or required additional assistance during or after onboarding.                                                                    | **High Risk**            |
| **Average Days to Convert**            |    8.9 days |      6.4 days | Users in the Treatment group converted **2.5 days faster** than those in the Control group. A shorter time-to-convert indicates that the new onboarding process helped users reach value more quickly.                                                                                                                  | **Positive Outcome**     |
| **Average Engagement Score**           |        57.0 |          62.9 | User engagement increased after the new onboarding experience, indicating that users interacted more actively with the product during the trial period.                                                                                                                                                                 | **Positive Outcome**     |
| **Average Revenue per Converted User** |   $1,630.10 |       $770.41 | Average revenue generated by each converted customer declined by approximately **52.7%**. While total conversions increased, the lower revenue per converted user suggests that the quality or spending behavior of new subscribers may differ from that of the Control group. Additional investigation is recommended. | **Moderate Risk**        |



## Overall Guardrail Assessment

The guardrail metrics present a mixed picture of the Treatment campaign.

### Positive Findings

* Users converted to paid subscriptions significantly faster.
* Engagement scores improved, indicating stronger interaction with the product during the trial period.
* The higher conversion rate suggests that the onboarding campaign effectively encouraged more users to subscribe.

### Areas of Concern

* The support ticket rate increased substantially, indicating a higher demand for customer assistance after the new onboarding experience.
* A slight increase in refund requests suggests that a small proportion of users may have been dissatisfied after converting.
* Average revenue per converted user declined considerably, indicating that the increase in conversion volume did not translate into proportionally higher revenue from each paying customer.



## Business Interpretation

The new onboarding campaign successfully improved user activation, engagement, and conversion. However, the evaluation of guardrail metrics indicates that these improvements were accompanied by increased operational costs and a reduction in revenue generated per converted customer.

These findings suggest that the treatment delivers meaningful business value but also introduces potential risks related to customer support demand and revenue quality. Before implementing a full rollout, the organization should investigate the causes of the increased support requests and lower revenue per converted user. Addressing these issues could improve the overall effectiveness of the onboarding experience while preserving the gains in conversion performance.

## Conclusion

The guardrail analysis demonstrates that the Treatment campaign should not be evaluated solely on its improvement in the North Star metric. While the campaign achieved a statistically significant increase in Trial-to-Paid Conversion Rate, the higher support ticket rate, increased refund rate, and lower average revenue per converted user indicate that additional refinement is advisable before a company-wide deployment.

