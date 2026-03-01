# Task 6: House Price Prediction with Linear Regression
### DevelopersHub AI/ML Engineering Internship

---

## Overview

This task walks through a complete regression workflow for predicting house prices from scratch. Rather than jumping straight to modeling, the focus was on doing the groundwork properly — cleaning the data, understanding what the features are actually telling us, and then training a Linear Regression model on a solid foundation. Performance was evaluated using MAE and RMSE to get a clear picture of how far off predictions typically land.

---

## Project Structure

```
task-6-house-price-prediction/
├── house_price_prediction.ipynb   # Main notebook with full workflow
├── dataset.csv                    # Dataset used for training and evaluation
├── requirements.txt               # Dependencies
└── README.md
```

---

## Setup & Usage

**1. Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/task-6-house-price-prediction.git
cd task-6-house-price-prediction
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Run the notebook**
```bash
jupyter notebook house_price_prediction.ipynb
```

---

## Dependencies

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

## Workflow

### 1. Data Cleaning & Preprocessing
Handled missing values, removed irrelevant columns, and ensured all features were in a suitable format for modeling. Clean inputs lead to more reliable outputs.

### 2. Exploratory Data Analysis (EDA)
Explored distributions and relationships across features to get an intuition for the data before any modeling took place. Visualizations here guided later decisions about which features to include.

### 3. Correlation Analysis
Generated a heatmap to identify which features have the strongest relationship with house prices. This helped highlight what the model is likely to lean on most heavily and flagged any multicollinearity worth watching.

### 4. Train-Test Split
Split the dataset into training and testing subsets to ensure the model is evaluated on data it has never seen — giving a more honest measure of real-world performance.

### 5. Model Training
Trained a **Linear Regression** model using scikit-learn on the preprocessed training data.

### 6. Model Evaluation
Assessed performance on the test set using two metrics:

| Metric | What It Measures |
|--------|-----------------|
| **MAE** (Mean Absolute Error) | Average magnitude of prediction errors in the same units as the target |
| **RMSE** (Root Mean Squared Error) | Similar to MAE but penalizes larger errors more heavily |

---

## Model

| Property | Details |
|----------|---------|
| Algorithm | Linear Regression |
| Library | Scikit-learn |
| Evaluation Metrics | MAE, RMSE |

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data loading and manipulation |
| NumPy | Numerical operations |
| Matplotlib & Seaborn | Visualizations and heatmaps |
| Scikit-learn | Model training and evaluation |

---

## What I Learned

This task made clear how much the quality of preprocessing affects model output. Linear Regression is interpretable and fast, but it's also sensitive to the quality of the data fed into it. The correlation heatmap was particularly useful — it turned an abstract question ("which features matter?") into something visual and immediately actionable. MAE and RMSE together gave a more complete picture of performance than either metric would alone.

---

## Author

M.Abeer Ahmed Siddiqui
DevelopersHub AI/ML Engineering Internship
