# kaggle_rainfall

# Binary Prediction with a Rainfall Dataset Playground Series - Season 5, Episode 3

### Performed steps: 
- EDA
- Feature Experimentation -> Lagged and Rolling features are not helpful, instead; combination of 2 features (interactive features) have additional forecasting power
- Model experimentation -> Simple Logistic Regression beat Hist. Gradient boosters, and stacked models (More complex models overfit the small dataset)
- HPO -> Optuna was used for HPO, for all experimented models, Logistic Regression with base parameters outperformed the optimized params

### Additional steps:
- Experimenting with more features, although 70+ features were tried.