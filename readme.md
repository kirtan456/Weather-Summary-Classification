# 📌 Overview

This project focuses on predicting weather summary categories using historical weather data and machine learning techniques. The dataset is preprocessed, analyzed through Exploratory Data Analysis (EDA), and used to train multiple classification models. To improve performance, similar weather summaries are grouped into broader categories, reducing class imbalance and enhancing prediction accuracy.

# 🎯 Objectives
- Classify weather conditions into meaningful summary categories.
- Perform data cleaning and preprocessing.
- Analyze weather patterns through EDA.
- Handle class imbalance by grouping similar weather summaries.
- Compare multiple machine learning algorithms.
- Evaluate model performance using classification metrics.
# 📂 Dataset Information
- Rows: 96,453
- Columns: 11
- Target Variable: Summary
- Problem Type: Multi-Class Classification
- Features
- Temperature (C)
- Apparent Temperature (C)
- Humidity
- Wind Speed (km/h)
- Wind Bearing (degrees)
- Visibility (km)
- Pressure (millibars)
- Daily Summary
- Precipitation Type
- Formatted Date
- Summary (Target)
# 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
# 📊 Exploratory Data Analysis (EDA)

The notebook includes:

- Dataset overview
- Missing value analysis
- Duplicate value removal
- Descriptive statistics
- Weather summary distribution
- Temperature distribution
- Humidity analysis
- Correlation heatmap
- Box plots
- Histograms
- Pair plots
# ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Handling missing values
- Removing duplicate records
- Label Encoding for categorical variables
- Grouping similar weather summaries into broader classes
- Feature engineering
- Train-Test Split
- Feature Scaling (where required)
# 🤖 Machine Learning Models

The following models are implemented and compared:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost Classifier
# 🔍 Model Evaluation

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report
