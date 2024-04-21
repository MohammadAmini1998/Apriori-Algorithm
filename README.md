# Frequent Pattern Mining with Apriori Algorithm

In this project, we apply frequent pattern mining on a market transaction dataset using the Apriori algorithm.

## Apriori Algorithm

The Apriori algorithm is a classic algorithm used for frequent item set mining and association rule learning over transactional databases. It was proposed by Agrawal and Srikant in 1994. The algorithm is designed to operate on databases containing transactions, where each transaction consists of a set of items.

### How Apriori Algorithm Works:

1. **Generating Candidate Itemsets:**
   - The algorithm starts by identifying the frequent individual items in the database (items having support greater than a threshold).
   - It then generates a set of candidate itemsets of length (k) from the frequent itemsets of length (k-1). This process is continued until no more new frequent itemsets can be generated.

2. **Scanning the Database:**
   - Once the candidate itemsets are generated, the algorithm scans the database to count the support of each candidate.
   - Support is the frequency of occurrence of an itemset in the database. It is calculated as the ratio of the number of transactions containing the itemset to the total number of transactions.

3. **Pruning:**
   - The algorithm eliminates candidates that fail to meet minimum support. This step reduces the search space and makes the algorithm more efficient.

4. **Repeating:**
   - The process is repeated until no more new frequent itemsets are identified.

### Example:
bread, milk
bread, diaper, beer, eggs
milk, diaper, beer, coke
bread, milk, diaper, beer
bread, milk, diaper, coke
With a minimum support of 2, we find:

1. Frequent itemsets of size 1: {bread}, {milk}, {diaper}, {beer}, {coke}
2. Frequent itemsets of size 2: {bread, milk}, {bread, diaper}, {milk, diaper}, {milk, beer}, {diaper, beer}, {diaper, coke}
3. Frequent itemsets of size 3: {bread, milk, diaper}, {bread, diaper, beer}, {milk, diaper, beer}
4. Frequent itemsets of size 4: {bread, milk, diaper, beer}

Consider the following transactions:
## Dataset
The market transaction dataset used for this project contains approximately 7500 transactions. It has about 7500 transactions. The dataset is provided in the repo as well but any dataset will do the job. 
## Results
![Screenshot (125)](https://github.com/MohammadAmini1998/Apriori-Algorithm/assets/49214384/aeeabab5-3265-42b6-b82e-8952079f8121)
![Screenshot (124)](https://github.com/MohammadAmini1998/Apriori-Algorithm/assets/49214384/75576173-9a8d-4299-b31b-83e7d20b7611)
![Screenshot (123)](https://github.com/MohammadAmini1998/Apriori-Algorithm/assets/49214384/b39c69ee-7e84-4793-bda1-eeb00d422e14)

## Contributions and Feedback

I welcome contributions, feedback, and suggestions for improvement! If you have any ideas, questions, or insights regarding this project, feel free to reach out and engage in discussions.

Let's continue exploring the exciting possibilities of Data Mining together! 🚀
