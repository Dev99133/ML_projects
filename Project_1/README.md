# Predictive Insight Engine — House Price Prediction

**Role:** Junior Data Scientist, Real Estate Analytics Firm
**Type:** Supervised Learning — Regression Techniques & Model Performance Analysis
**Duration:** 6 Hours | **Dataset:** 4,200 property records

## 📌 Objective
Design, implement, analyze and evaluate multiple supervised learning models to predict house
prices from property features, and explain why certain models outperform others.

## 📁 Repository Structure
```
├── predictive_insight_engine.ipynb   # Full practical implementation (Parts B–I)
├── RealEstate_HousePrice_Dataset_4200.csv
├── Theory_Concepts_PartA.pdf         # Part A conceptual/theory answers
├── plot_*.png                        # Exported charts referenced in the notebook
└── README.md
```

## 🧠 Contents
- **Part A** — Theory: supervised learning, regression vs classification, simple linear
  regression, assumptions, bias–variance trade-off, overfitting/underfitting → see
  `Theory_Concepts_PartA.pdf`
- **Part B** — Dataset understanding, feature/target identification, visualization, train/test split
- **Part C** — Simple Linear Regression (`area_sqft` → `house_price_inr`), assumption validation
- **Part D** — Model evaluation metrics: MSE, MAE, RMSE, R², Adjusted R²
- **Part E** — Multiple Linear Regression (all features) and comparison to Simple Linear Regression
- **Part F** — Polynomial Regression (degree 2 & 3), overfitting/underfitting inspection
- **Part G** — Gradient Descent from scratch: Batch, Stochastic (SGD), and Mini-Batch
- **Part H** — Bias–variance and model diagnostics across all models
- **Part I** — Final analysis, business interpretation, and recommendations

## 🏆 Key Result
**Multiple Linear Regression** was the best-performing model, achieving the lowest error
(MSE/MAE/RMSE) and highest Adjusted R² by using all ten property features instead of area alone.

## ⚙️ How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook predictive_insight_engine.ipynb
```

## 🎥 Submission Components
- Source code: `predictive_insight_engine.ipynb`
- Theory document: `Theory_Concepts_PartA.pdf`
- Model evaluation results & plots: embedded in the notebook + exported `plot_*.png` files
- Recorded video walkthrough: *(add your Google Drive / YouTube unlisted link here)*

