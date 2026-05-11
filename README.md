# HySEM
HySEM (Hybrid Ensemble Stacked Ensemble Model) = An efficient ML model with constitents from bagging, boosting and kernel based models.
Detailed theory and explanations can be seen from https://doi.org/10.1002/eer2.70030.
Novelty of this model is that it works well on all fronts of data analysis. 
Boosting and Bagging algorithms like XgBoost, Random Forest works well with global parameters and perform well on evaluation metrics like R2, MSE and MAE that emphasize overall prediction errors. But do not perform well on metrics like REC curve and AOC. But SVM by design performs well on metrics like REC and AOC. 
So by using base learners that have their own unique strength stemming from its design HySEM is efficient in performing with variety of the tasks.
