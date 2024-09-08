# Project Title: A/A/B Test and Sales Funnel Analysis for Food App

**Overview:** This project focuses on analyzing user behavior in a food product app and evaluating the results of an A/A/B test to determine the impact of a font change on sales. The analysis aims to understand how users move through the sales funnel, identify where potential customers drop off, and evaluate whether changing the app’s fonts improves user behavior. The project includes event funnel analysis and statistical hypothesis testing on multiple user actions.

**Key Skills & Concepts:**

* Data Preprocessing: Cleaned and processed event log data, ensuring correct data types, and handled missing values.
* Sales Funnel Analysis: Investigated the user journey through key stages of the app, from initial interaction to payment, identifying significant drop-off points.
* A/A/B Testing: Performed statistical hypothesis testing to compare user behavior between two control groups (old fonts) and one test group (new fonts).
* Event Analysis: Analyzed the frequency and proportion of user actions to evaluate how effectively users moved through the sales funnel.
* Statistical Testing: Conducted ratio tests to check for statistically significant differences between the control and test groups, evaluating the impact of font changes on user behavior.

**Key Insights:**

* Sales Funnel Drop-Off: The largest drop-off of users occurred between the main screen and the offer screen, leading to significant customer loss before purchases.
* A/A/B Test Results: No statistically significant differences were found between the two control groups or between the test group and the control groups, indicating that the font change did not improve user behavior or sales.
* Significance Level: Recommended setting a stricter significance level of 0.01 (instead of 0.1) to reduce the probability of false positives in future experiments.

**Tools Used:**

* Python (Pandas, Matplotlib, SciPy): Data manipulation, visualization, and statistical testing.
* A/A/B Testing: Implemented to compare the performance of different user groups.
