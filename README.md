# dboost

Stocastic Dummy Boosting:
I randomly create dummy variables by randomly splitting column features. It's basically a stump. Then I do Ridge regression which is my weak learner for boosting. Then it's just GBM from there.
