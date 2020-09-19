# IDS
IDS with CICIDS2017 dataset based on tree-based classifiers

This work is dedicated to Intrusion Detection Systems for IoT
Environments based on Network Traffic Analysis. 
It is important to choose the appropriate method of identification of
modern attacks. The aim of this thesis work is to demonstrate the abilities of
tree-based classification algorithms for Intrusion Detection Systems and to
provide the reasons why these classification algorithms are highly suitable
for considered problem.
Based on the review of the literature CICIDS2017 dataset, Decision
Tree, Random Forest, XGBClassifier classification algorithms were decided
to be reviewed and analysed.

CICIDSFlow.ipynb contains data preprocessing phase.
dec_tree_rand_for.ipynb contains classification with decision tree and random forest.
randomforest.ipynb contains classification with random forest.
xgboostclf.ipynb contains classification with xgbclassifier.

All hiperparameters presented in files represent the best ones regarding to model performance and computational resources(xgbclassifier can be improved having high computational power).
