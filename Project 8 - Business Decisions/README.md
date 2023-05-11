# Project 8 - Online store. Making Business Decisions Based on Data

**Technologies and Tools** - Python, Jupyter, Pandas, Numpy, Seaborn, Matplotlib, Plotly, Scipy

**Goal:** The main objectives of the project are hypothesis prioritization and analyzing the results of an A/B-test.

**Project Description**

You are an analyst at a big online store. Together with the marketing department, you've compiled a list of hypotheses that may help boost revenue. You need to prioritize these hypotheses, launch an A/B test, and analyze the results.

## Overall Conclusion

We have 9 hypotheses for increasing revenue. The most promising of them in terms of factors of influence, confidence and resource costs:

- 7.Add a subscription form to all the main pages. This will help you compile a mailing list
- 2.Add product recommendation blocks to the store's site. This will increase conversion and average purchase size
- 6.Show banners with current offers and sales on the main page. This will boost conversion
- 0.Add two new channels for attracting traffic. This will bring 30% more users

A preliminary analysis of the results of the A / B test showed that it included only 2 groups: A and B. But users who fell into both tested groups also took part in the A / B testing: they were about 5% of all users. We don't know how this happened, who are these users and why are they represented in both of these groups? If we remove these users from the "order" data, we will mess up the results because we cannot identify the users in the "visit" data. Which in turn affects our conversion rate in the future. Therefore, these users were left and it was further verified that the exclusion of these users does not critically affect the study.

Revenue increases almost uniformly throughout the test. Moreover, the first 5 days in both groups there was an approximately equal value of revenue. And then the graphs of cumulative revenue in both groups at several points began to rise sharply (in group B, the jumps were more pronounced). Further, in the process of analysis, it was revealed that such jumps are due to both anomalous users who made a lot of orders (3 or more - up to 11 orders), and users who bought very expensive goods.

The average check in group A becomes uniform approximately from the middle to the end of the test, and in group B, after a significant jump, it begins to slowly decrease. Perhaps this is due to large or expensive purchases. Until mid-August, both groups had ups and downs (more in group B than in group A).

Since August 7 the graph of cumulative conversion by groups looks almost symmetrical. Until August 4 there was a strong surge in both groups. In subsequent periods, the conversions of both groups settled at a certain level (approximately after August 9-11) with a clear predominance of the cumulative conversion of group B over the cumulative conversion of group A.

## Recommendations

It is recommended to stop the test and record the victory of group B. There is no point in continuing the test, because the main indicators have reached and fluctuate near certain levels, and no changes are predicted, other things being equal.

LINK: [Detailed Project](Project_8_BA.ipynb)


## Scope of activities
A/B-testing, Online store business, Internet Services, Marketing, Business services [b2b], Marketing analyst, Product Analyst.

