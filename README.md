# Binary-Classification-with-a-Bank-Dataset

Achieved a score of ~0.96

[Competion Link](https://www.kaggle.com/competitions/playground-series-s5e8/overview)

Goal: Predict whether a client will subscribe to a bank term deposit.

## Project Workflow:

### Data Preprocessing

- Encoded categorical variables (Label Encoding).

- Scaled numerical features (StandardScaler).

### Exploratory Data Analysis (EDA)

- Correlation analysis between features and target.

- PCA-based visualization of feature space.

### Feature Engineering

- Feature importance visualization using XGBoost.

- Correlation heatmap for categorical & numerical features.

### Modeling

Implemented multiple models:

- Random Forest

- AdaBoost

- XGBoost

- LGB

### Key Results

- Tree-based models performed the best.

- XGBoost+LGB gave the highest performance.

### Visualizations

- Correlation heatmap between features & target.

- PCA scatterplot (2D feature reduction).

- Feature importance plots (LightGBM).

### Tech Stack

- Language: Python

- Libraries: scikit-learn, XGBoost, matplotlib, seaborn, pandas, numpy, plotly
