# e-commerce-hack
E-commerce Price prediction hackathon
Hackathon for predicting prices.
Target variable was highly left-skewed, due to which the output also was getting left-skewed. So logarithmic transformation to normalise the target variable. 2 models XGBoost and LGBM used. Fine-tuned the models which were giving good cross-validation score through early stopping. In the end blended the result of all 2 models to get final score.
