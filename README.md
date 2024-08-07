# Data_Analysis
Bank Statements (P1- BankStatements.json) – 50 Marks

1.  Transaction Analysis: 
   a) What is the total number of transactions made over the year?

Total number of transactions: 985

  b) What is the distribution of transaction amounts (e.g., small vs. large transactions)? (define small and large transactions by yourself)

we can use multiple ways to determine small and large transactions 
1. Exploratory data analysis: Visualize the Data: Create visualizations like histograms or box plots to see the distribution of transaction amounts.we can determine the threshold value
2. statistical methods: Mean and Median: Calculate the mean and median transaction amounts. The median is particularly useful if the data is skewed.
3.ML algorithms: K Means clustering is suitable for segmenting transactions into small and large categories. It iteratively groups transactions based on their amounts creating two  distinct clusters.By analysing the average transactionvalues with each cluster you can effectively label them as small and large.
3.Naive approach: Alternatively, set fixed thresholds
