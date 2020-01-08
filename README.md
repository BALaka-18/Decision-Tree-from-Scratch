# Decision-Tree-from-Scratch -----> 1. For a toy dataset. 2. Generalizing it for any dataset.

# 1. For a toy dataset : 
Writing a customized decision tree from scratch for a specific sample dataset only. 
Writing the decision tree helped me understand the concept of Gini impurity and Information gain of a decision node.
Questions were tailored according to the dataset. Will vary from dataset to dataset.
Splitting tailored according to questions asked and the dataset.
Further implementing the decision tree to check if classification was successful or not.

# 2. Generalizing decision tree split for any dataset :
Dataset used for initial design of algorithm : play_tennis.csv
Calculating information gain for all feature columns iteratively to obatin the best split.

Entropy (parent) = (-)Summation{p x log(p)}

Weighted entropy (children after split) = [(p_leftbranch x entropy_leftnode) + (p_righttbranch x entropy_rightnode)], where, p_leftbranch = (no. of examples in left branch after split/total no. in parent)

Therefore, information gain = Entropy (parent) - Weighted entropy (children after split)

The feature column with highest information gain is selected for the split.
