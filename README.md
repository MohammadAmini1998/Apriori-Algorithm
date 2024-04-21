# Frequent Pattern Mining with Apriori Algorithm

In this project, we apply frequent pattern mining on a market transaction dataset using the Apriori algorithm from scratch.

## Apriori Algorithm

The Apriori algorithm is a classic algorithm used for frequent item set mining and association rule learning over transactional databases. It proceeds by identifying the frequent individual items in the database and extending them to larger and larger item sets as long as those item sets appear sufficiently often in the database.

### How Apriori Algorithm Works:

1. **Generating Candidate Itemsets:**
   - The algorithm generates a set of candidate itemsets of length (k) from the frequent itemsets of length (k-1).

2. **Scanning the Database:**
   - It counts the support of each candidate by scanning the database.

3. **Pruning:**
   - It eliminates candidates that fail to meet minimum support.

4. **Repeating:**
   - The process is repeated until no more new frequent itemsets are identified.
## Dataset
The market transaction dataset used for this project contains approximately 7500 transactions. It has about 7500 transactions. The dataset is provided in the repo as well but any dataset will do the job. 

## Contributions and Feedback

I welcome contributions, feedback, and suggestions for improvement! If you have any ideas, questions, or insights regarding this project, feel free to reach out and engage in discussions.

Let's continue exploring the exciting possibilities of Data Mining together! 🚀
