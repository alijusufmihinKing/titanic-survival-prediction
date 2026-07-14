In the first approach, we used RandomForest with a train/test split, 
which gave us a MAE of 0.139. In the second approach, we used XGBoost 
with Cross-Validation (5 folds), which gave a MAE of 0.172. 

Although XGBoost and Cross-Validation are generally considered more 
advanced methods, RandomForest performed better here. The reason is 
that XGBoost works best on large datasets — on a small dataset like 
Titanic (891 rows), it cannot reach its full potential.

Conclusion: RandomForest is the better choice for this dataset.
