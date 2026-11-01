---
title: "Predictive Analytics & Machine Learning"
impact: CRITICAL
impactDescription: "Core MBA framework, foundational to domain"
tags: analytics, economics, learning, machine, marketing, predictive
---

**Business Applications**:

- Customer lifetime value prediction: Prioritize retention and acquisition efforts
- Churn prediction: Identify at-risk customers for intervention
- Price elasticity: Understand demand response to pricing; optimize prices
- Demand forecasting: Predict future demand from drivers (seasonality, price, promotions)
- Credit scoring: Predict loan default risk; optimize lending decisions
- Inventory demand: Predict demand for SKUs to optimize stock levels
- Quality prediction: Predict likelihood of defects to prevent failures

**Machine Learning Workflow**:

1. Problem Definition: Regression (continuous) or classification (binary/multiclass)?
2. Data Collection: Assemble historical data with outcomes
3. Feature Engineering: Create variables predicting outcome (domain knowledge critical)
4. Model Selection: Try multiple algorithms (linear, tree-based, ensemble)
5. Training: Fit model to historical data
6. Validation: Test on held-out data; tune hyperparameters
7. Deployment: Apply to new data for decisions
8. Monitoring: Track model performance; retrain when accuracy drifts

**Model Types**:

- Linear Regression: Assumes linear relationship; interpretable, fast
- Logistic Regression: Classification (0/1); outputs probability
- Decision Trees: Interpretable; can overfit; prone to instability
- Random Forests: Ensemble of trees; robust; less interpretable
- Neural Networks: Flexible; requires much data; black-box
- Gradient Boosting: State-of-art for structured data; XGBoost, LightGBM

**Model Validation**: 

- Train/test splits: 70% training, 30% test (prevents overfitting)
- Cross-validation (k-fold): Use k different train/test splits; better use of limited data
- Time series splits: Use past to predict future (don't train on future)
- Metrics: Accuracy, precision, recall, F1, AUC-ROC

**Overfitting**: Model fits training data perfectly but fails on new data; detected when test performance much worse than training. Prevention: regularization (L1, L2), early stopping, simpler models.

**Underfitting**: Model too simple, missing real relationships; detected by poor training and test performance. Solution: more complex model, better features.

**Feature Importance**: Which variables drive predictions? Helps understand driver of outcome and prevents false correlations.

**Causal Inference vs. Correlation**:

- Correlation: X and Y move together; doesn't prove causation
- Causation: X actually causes Y; change in X leads to change in Y
- Common pitfalls: Confounding variable affects both X and Y, creating spurious correlation
- Methods to establish causation: Randomized experiments (gold standard), instrumental variables, natural experiments, regression discontinuity
- Prediction vs. Causation: Predictive models work with correlation; causal models needed to understand "what if" interventions

---