📁 Project Structure
Data_Exploration.ipynb
Exploratory Data Analysis (EDA):
•	Dataset overview and structure
•	Missing value analysis
•	Class distribution analysis (severity imbalance)
•	Temporal feature extraction (Hour, Day, etc.)
•	Correlation analysis
•	Feature distribution visualizations
•	Infrastructure and weather feature analysis

Baseline_Modeling.ipynb
Initial benchmark models:
•	Logistic Regression (multinomial)
•	Random Forest Classifier
•	XGBoost Classifier
•	LSTM
•	Ordinal Regression
•	Deep Learning
•	Evaluation using:
o	Precision
o	Recall
o	F1-score
o	Confusion Matrix
•	Baseline comparison across severity classes

Feature_Selection.ipynb
Feature engineering and selection:
•	One-hot encoding of categorical variables
•	Correlation-based filtering
•	Tree-based feature importance
•	XGBoost feature importance ranking
•	Random Forest Feature Importance
•	Selection of top predictive variables

Weight work using XGBoost.ipynb
Advanced modelling with imbalance handling:
•	SMOTE oversampling
•	Class weighting
•	XGBoost training
•	Hyperparameter tuning
•	Cross-validation
•	Feature importance analysis

Model After Class Imbalance tunning.ipynb
After reclassing the data set to address severity 2 class imbalance:
•	Logistic regression
•	Random Forest
•	LSTM
•	Cat Boost
•	XGBoost
