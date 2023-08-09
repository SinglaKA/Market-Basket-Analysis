# Market-Basket-Analysis
A method/technique of Data Analysis for retail and marketing purposes. This explores the customer's purchasing behaviour.
This uncovers which items are bought frequently and together. This is a great way for effective sales and marketing and helps companies understand when and how much discount/sales needed to be drawn upon various items.
The only condition for this analysis is that the items should be brought together in any transaction. 

The method works on the basis of Association rules. 
These rules identify patterns when two items are bought together. To identify the patterns, we have algorithms like Apriori Algorithm and FP Growth ALgorithm. 
Antecedent and Consequent are the items that are bought together in the cart. For ex: If a person buys bread, then the person will buy milk too.
If part is called antecedent and then part is called consequent. 
These two algorithms are used in the analysis of the repository. 
Metrics used to understand these algorithms:
1. Support: It denotes the frequency of two or more items bought together. Mathematically, the number of transactions in which two or more items are together to the total number of transactions.
2. Confidence: It is the likelihood of the occurrence of the consequent in the basket given that antecedent is already in the cart. This value denotes the confidence level or probability that the items will be bought together.
3. Lift: This is Confidence to Support of consequent. This gives a value that the items will be checked out by the customers.
