# Comparison of AB Testing and Bidding Methods
Facebook recently introduced a new bidding type called "average bidding" as an alternative to the existing "maximum bidding" bidding type. One of our clients, -.com, decided to test this new feature and wants to conduct an A/B test to determine if average bidding brings more conversions than maximum bidding. The A/B test has been running for 1 month, and now -.com is expecting you to analyze the results of this A/B test. The ultimate success metric for -.com is Purchase. Therefore, Purchase metric should be the focus for statistical tests.


## Miuul Data Science and Machine Learning Bootcamp Assignment
## Dataset
This dataset contains information about a company's website, including the number of ads viewed and clicked by users, as well as revenue generated from these ads. There are two separate data sets, one for the control group and one for the test group. These data sets are located on separate sheets of the ab_testing.xlsx Excel file. Maximum Bidding was applied to the control group, while Average Bidding was applied to the test group.

## Methods
Shapiro-Wilk test for normality assumption

Levene test for homogeneity of variances assumption

Parametric test
