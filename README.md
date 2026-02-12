# NFL-Player-Performance-Volatility: Boom or Bust Analysis

### 📌 Objective

This project analyzes the **volatility of NFL player performance** by identifying *Boom or Bust* patterns across weekly games. The goal is to distinguish between consistently reliable players and those with high variance in performance outcomes.

### 💡 Motivation

Player performance inconsistency can significantly impact **team strategy, game outcomes, and fantasy football decisions**. By quantifying volatility and uncovering the drivers behind performance swings, this project provides **actionable, data-driven insights** for:

* NFL teams and analysts evaluating player reliability
* Fantasy football managers making roster and lineup decisions
* Sports data scientists studying performance stability

Ultimately, this work enhances understanding of **player consistency, upside potential, and risk profiles**.

### Dependencies

  
The libraries needed are matplotlib, numpy, pandas, scipy, scikit-learn, seaborn, plotly, yellowbrick, and nfl-data-py.

---

### 🧠 Methodology

#### 📊 Data

Weekly NFL player and team statistics were used to model performance outcomes and variability over time.

#### ⚙️ Modeling Approach

Multiple machine learning models were developed and compared to evaluate both **linear and nonlinear relationships** in player performance:

* **XGBoost** – Achieved **81% accuracy**, capturing complex nonlinear interactions
* **Logistic Regression** – Baseline linear classification model
* **LASSO (L1-Regularized Regression)** – Used for feature selection and interpretability

#### 🛠 Feature Engineering

Custom features were created to better represent:

* Performance trends over time
* Game context and team dynamics
* Variability-related indicators

This allowed deeper analysis of **which metrics contribute most to performance swings**.

---

### 🔍 Key Outcomes

* Identified **Boom or Bust performance patterns** across players
* Compared effectiveness of **nonlinear vs. linear models**
* Determined **key performance indicators (KPIs)** that strongly influence win probability and performance variability
* Demonstrated the value of machine learning in evaluating **player risk and consistency**, not just average performance

---

### 🚀 Applications

This framework can be extended to:

* Player scouting and contract valuation
* Fantasy football draft and lineup optimization
* Sports betting and predictive performance modeling
* Risk-adjusted player evaluation metrics

### Installing

You can download my program through the "cmse890finalproject1.ipynb" file attached to the repository.

## Authors

Contributors names and contact info

* Kendall Andrews - Author
* NFL Python Package - Pypi - nfl-data-py 

---
