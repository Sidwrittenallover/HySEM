# HySEM

HySEM (Hybrid Ensemble Stacked Ensemble Model) is an efficient machine learning model consisting of constituents from bagging, boosting, and kernel-based models.  

Detailed theory and explanations can be found at:  
https://doi.org/10.1002/eer2.70030

## Novelty of HySEM

The novelty of this model lies in its capability to perform efficiently across multiple fronts of data analysis.

Boosting and bagging algorithms such as:

- XGBoost
- Random Forest

generally perform well in capturing global relationships within the data and achieve strong performance in evaluation metrics such as:

- $R^2$
- MSE
- MAE

These metrics primarily emphasize overall prediction accuracy and global error minimization.

However, such models may not perform equally well on metrics such as:

- REC (Regression Error Characteristic) curve
- AOC (Area Over the Curve)

On the other hand, Support Vector Machine (SVM), by design, demonstrates superior performance in REC- and AOC-based evaluations due to its kernel-based learning characteristics and local generalization capability.

Therefore, by integrating base learners with unique strengths arising from their individual algorithmic designs, HySEM achieves robust and balanced performance across a variety of predictive tasks and evaluation criteria.
