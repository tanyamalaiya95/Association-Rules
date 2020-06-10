# Association-Rules: Cincinnati Zoo Data

## Data
The data being used for Association Rules is the Cincinnati Zoo Dataset, which consists of the sales of edible items from the Cincinnati Zoo by visitors. The data consists of 19076 rows and 119 columns, with the first column being the unique identifier column for each transaction.
## Goal and Background
The objective of this analysis is to examine the data and get insight into buyer behavior or purchasing patterns of customers.
## Approach
Initially, exploratory data analysis is conducted. Next, Apriori algorithm is used for generating association rules with pre-defined minimum thresholds for support and confidence as 0.3% and 90% respectively. We iterate with these thresholds and discover newer rules and interpret the findings.
## Major Findings
The raw data is quite sparse (2.2% density), with the maximum number of items in a transaction being 15 (out of totally 118 items available), and most of the transactions being of the size 2 or less. The most frequently sold items are bottled water, cheese slice, and drinks. With the initial parameters, only 8 rules are discovered. By reducing the threshold for either support or confidence, more rules can be discovered, and some may have higher lift parameters.

