# QuickBite Customer Value Analysis —  Summary

## Project Overview
QuickBite operates across 10 Indian cities in three city tiers. Before analyzing customer behavior, I cleaned the dataset of 2,000 customers by fixing missing entries and handling impossible values (such as unrealistic ages and extreme delivery delays) so that all business numbers can be trusted.

## 5 Key Insights

1. **Order Frequency Drives Annual Spend:** 
   The number of orders a customer places in a year (`orders_last_12m`) has the strongest positive relationship with `annual_spend`. Customers who order regularly spend significantly more than one-time high-basket buyers.

2. **Revenue is Heavily Concentrated in a Small Group:** 
   Customer spending is heavily right-skewed, the average spend is much higher than the median because of a small group of high-value VIP users. Around the top 20% of customers contribute roughly 60% of QuickBite's total revenue.

3. **Most Deliveries Take ~32 Minutes, But ~16% Are Late:** 
   The median delivery time is 32.2 minutes, and about 40% of orders arrive in 30 minutes or less. However, around 15.6% of deliveries take more than 45 minutes, creating a long tail of delayed orders.

4. **Slow Deliveries Hurt Customer Ratings and Feedback:** 
   Longer delivery times are linked to lower customer ratings. Additionally, missing ratings occur more often when deliveries are delayed, meaning dissatisfied customers often skip rating altogether instead of leaving feedback.

5. **Data Entry Gaps Were Distorting Business Metrics:** 
   Several columns had 4% to 12% missing values along with a few impossible entries (such as an age of 150). Cleaning these errors first prevented false averages and gave a realistic picture of customer behavior.

---

## 2 Actionable Recommendations

1. **Launch a Loyalty & Repeat-Order Program for Mid-Tier Users:** 
   Since order frequency is the biggest driver of revenue and our top 20% customers bring in ~60% of sales, QuickBite should introduce targeted perks (like free delivery passes or milestone rewards after every 5 orders) to turn occasional buyers into regular subscribers.

2. **Fix the >45-Minute Delivery Bottleneck in Slow Zones:**
   Because 15.6% of orders cross 45 minutes and directly hurt customer ratings, operations should identify the cities and peak hours where delays happen most, improve rider allocation there, and trigger proactive support whenever an order passes 40 minutes.
