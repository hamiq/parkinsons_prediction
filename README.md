# 🧠 Classifying Parkinson's Disease

This is a model building project to detect the onset of Parkinson's disease, a nervous system disorder that negatively affects movement, using XGBClassifier.

XGBClassifier uses a Gradient Boosting algorithm to build a classification model, which combines the outputs of many weak classifiers to produce a single, stronger one (i.e. one whose mean squared error is the smallest). A weak classifier, like a decision tree, is one whose error rate is at least slightly better than random guessing. In gradient boosting, each successive application is thought to correct the errors of its predecessor. Overall, the algorithm can be thought of as introducing a loss function and finding a local minimum of this function by iterating through each weak classifier.

The generation and analysis of the model built in this project is described in the Python notebook file.

## 🛠️ Tools used:
- scikit-learn
- XGBoost
