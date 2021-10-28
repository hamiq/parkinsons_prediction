# Classifying Parkinson's Disease
Model building to detect onset of Parkinson's disease

XGBClassifier uses a Gradient Boosting algorithm to build a classification model. Gradient boosting combines the outputs of many weak classifiers to produce a single, stronger one (i.e. one whose mean squared error is the smallest). A weak classifier, like a decision tree, is one whose error rate is at least slightly better than random guessing. In gradient boosting, each successive application is thought to correct the errors of its predecessor. Overall, the algorithm can be thought of as introducing a loss function and finding a local minimum of this function by iterating through each weak classifier.
