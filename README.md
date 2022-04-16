# Market-Basket-Analysis
Market Basket Analysis in R for Groceries dataset

Each line of the dataset represent a receipt from a customer's basket.

# Αssociation rule is a relationship where {i1,i2} ⇒ i3 (if you put i1 & i2 in the basket you might put i3 as well)

# Support measures the frequency of the relationship in the dataset. 
# Ιt tells us what percentage of transactions contain the combination of items A and B. 
# e.g.purchasing fish and lemons together


# Confidence measures the probability that the association rule will be correct, 
# e.g., A = > B how many transactions that have bread (A) also have butter (B).

# Lift measures the effectiveness of the rule in finding consequents.

# Some general benchmarks:

# Lift < 1 does not indicate a cross selling opportunity

# Lift (A => B) = 1 means that within a set of elements there is no correlation.
# Lift (A = > B) > 1 means a positive correlation is more commonly purchased between the products in the product set, i.e. in items A and B.
# Lift(A =>B) < 1 means that it is unlikely to be purchased together for the negative correlation of the itemset, i.e. the products in the item set, A, and B.

# Drawback of confidence
# Confidence does not measure if the association between A and B is random or not. Whereas, Lift measures the strength of association between two items.

