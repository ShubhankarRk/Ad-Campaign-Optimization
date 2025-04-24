# Ad Campaign Optimization

Report: A/B Testing of Average Bidding vs. Maximum Bidding Models
 

Executive Summary:

This report analyzes the performance of Average Bidding and Maximum Bidding models through an A/B test conducted over a month. The analysis evaluates key metrics such as Click-Through Rate (CTR), Conversion Rate (CR), Cost Per Click (CPC), and Cost Per Acquisition (CPA). Using the Mann-Whitney U Test, the study determines statistically significant differences between the two bidding strategies, providing actionable insights for optimizing future campaigns.
 
Key Questions
1.	Which bidding model is better at attracting clicks, measured by the Click-Through Rate (CTR), which is the percentage of impressions that result in website clicks?
2.	Do the two models differ significantly in their ability to convert clicks into purchases, as indicated by the Conversion Rate (CR)?
3.	How cost-efficient are the two models in generating clicks and purchases, as measured by Cost Per Click (CPC) and Cost Per Acquisition (CPA)?
4.	What strategic insights can help optimize bidding strategies for better performance?
 

Dataset Overview
•	Datasets: test_group.csv, control_group.csv
•	Total Records: 60 (30 records per group)
•	Time Period: One month
•	Key Columns: Date, Spend [USD], # of Impressions, # of Website Clicks, # of Purchase
•	Removed Columns: Reach, # of Searches, # of View Content, # of Add to Cart (irrelevant to analysis)
 

Analysis and Insights
1. Metric Calculations
The following metrics were calculated for both groups:
•	CTR (Click-Through Rate): Measures ad effectiveness in attracting clicks. 
•	CR (Conversion Rate): Indicates the percentage of clicks resulting in purchases. 
•	CPC (Cost Per Click): Assesses efficiency of spend in generating clicks. 
•	CPA (Cost Per Acquisition): Evaluates the cost of acquiring a customer. 
2. Normality Testing
•	Shapiro-Wilk Test: Used to check the normality of metrics in both groups.
•	Results: All metrics failed the normality test (), indicating the need for non-parametric testing.
3. Hypothesis Testing
•	Test Used: Mann-Whitney U Test (non-parametric)
•	Null Hypothesis (H0): There is no difference between Average Bidding and Maximum Bidding.
•	Alternative Hypothesis (H1): There is a significant difference between the two bidding models.
Results:
•	CTR: Statistically significant difference (), with Average Bidding outperforming Maximum Bidding.
•	CR, CPC, CPA: No statistically significant differences ().
 

Observations and Recommendations
Observations
•	CTR: Average Bidding showed a significantly higher CTR (5% improvement over Maximum Bidding), indicating better ad effectiveness in attracting clicks.
•	CR and CPA: No significant differences, suggesting both models perform similarly in converting clicks to purchases and acquiring customers.
•	CPC: Average Bidding is marginally more cost-efficient in generating clicks, though not statistically significant.
Recommendations
1.	Adopt Average Bidding: Implement Average Bidding for campaigns focused on maximizing CTR.
2.	Further Analysis: Investigate factors influencing conversion rates to enhance performance across metrics.
3.	A/B Test Refinements: Conduct additional tests with larger datasets or over longer timeframes to confirm results.
 Next Steps
1.	Expand the dataset by running the A/B test over a longer period.
2.	Perform segmentation analysis to identify groups where Average Bidding performs better.
3.	Explore additional metrics, such as ROI or lifetime value, for a comprehensive evaluation of bidding models.
 
This report provides actionable insights for optimizing online advertising campaigns, highlighting the potential of Average Bidding in improving CTR while maintaining efficiency across other metrics.


