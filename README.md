# Debate Performance Analytics
An R-based data science project analyzing speaker observations to predict individual and team performance in competitive debating using fixed-effects models, TF-IDF text analysis, and XGBoost machine learning.

Project Structure

- 0_data_processing.ipynb: Data cleaning and feature engineering (rolling averages, cumulative stats).
- 1_motion_bias_model.ipynb: TF-IDF text analysis and XGBoost to identify structural advantages in debate topics.
- 2_points_model.ipynb: Predictive modeling of speaker and team performance using XGBoost.
- Research_Paper.pdf: Detailed methodology, including the Econometric Fixed-Effects (FE) analysis (note: FE code is currently excluded from notebooks).

Key Findings

- Individual: Teammate quality is the strongest predictor of speaker points.
- Teams: XGBoost predicts team wins with 73.6% accuracy, significantly outperforming linear models.

Requirements

- Language: R
- Main Libraries: xgboost, dplyr, tidytext, ggplot2
