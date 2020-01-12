# decision_tree_implementation
Python implementation from scratch - Decision Trees

Here we implement binary Decision Trees for regression and classification. The file dtree.py has all the functionality in following classes:

1) DecisionNode : class that defines a decision node.
2) LeafNode : class that defines leaves of the tree.
3) bestsplit : function that gives the best split point using gini / MSE criteria. We take only a subset of features for each split and randomly choose 11 datapoints to find the best split point. This increases the speed of our algorithm greatly.
4) DecisionTree : class that constructs the decision tree recursively, using the best split point obtained from bestsplit function.
5) RegressionTree621 / ClassifierTree621 : classes built upon DecisionTree class that encapsulate functionalities like fit(), predict() etc.

File test_dtree.py has tests to run and compare results from our implementation and check them against that from scikit-learn.

Thanks to Prof. [Terence Parr](https://github.com/parrt) for his guidance and support in this school project.