# Frequent Pattern Mining with Apriori Algorithm

In this project, we apply frequent pattern mining on a market transaction dataset using the Apriori algorithm.

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
