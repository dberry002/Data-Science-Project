Predicting Premier League Team Success from Midseason Performance
This project explores whether a Premier League team's midseason performance metrics can reliably predict their final point total at the end of the season. Using data from five EPL seasons (2019–2024), we built and compared multiple statistical models to evaluate predictive accuracy, including:

Simple Linear Regression using goal differential

Multiple Linear Regression with key midseason indicators (goal differential, goals against, win percentage)

LASSO Regression to identify the most impactful features while penalizing less informative ones

🔍 Key Findings
Goal differential and defensive metrics (especially goals against) are strong predictors of final points.

Multiple regression outperforms simple regression by incorporating more relevant variables.

LASSO regression confirms that Wins, Losses, and Attack-Defense Ratio (ADR) are top predictors.

📈 Methods Used
Exploratory Data Analysis (EDA) and correlation heatmaps

Feature engineering from match stats

Cross-validation (train/test split and 10-fold CV)

LASSO regression using ElasticNetCV with grouped K-folds to prevent data leakage across seasons

📁 Files Included
PL_data.csv: Processed dataset with engineered features

final_report.qmd: Quarto notebook with complete analysis and code

Visualizations (heatmaps, regression plots, LASSO coefficient plots)

💡 Future Work
Use match-level time series data to model performance trends more dynamically

Incorporate additional features like injuries, transfers, or managerial changes

Extend analysis to other leagues or seasons
