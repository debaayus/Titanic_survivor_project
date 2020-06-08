# Titanic_survivor_project

Attempted the starter Kaggle project with various implementations with promising results for an ensmeble classifier model

I tried the MLPC classifier however, it does not work well due to less quantity of data which causes high training performance but poor generalization. Tree based classifiers are more suitable for this problem and work better than other algorithms.
Few of the classifiers used:
1. XGBoost
2. Randomised Forest Trees
3. Decision Trees
4. CatBoost

The best performing classifier hyper-parameters were chosen by a grid search algroithm.

I perfomed feature engineering for favourable results which included:
1. Created a new feature - family size.
2. Converted few categories to one-hot-encoders.
3. Used correlation tables to weed out certain features.
4. Data imputation
