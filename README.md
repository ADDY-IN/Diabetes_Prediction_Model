<h1 align="center"><b>🩺 Diabetes Prediction Model</b></h1>

<p align="center">
Predict the likelihood of diabetes from routine clinical parameters using classic ML models.<br>
Clean pipeline • Solid baselines • Reproducible results ⚡
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white">
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-ML-FF9F1C?logo=scikitlearn&logoColor=white">
  <img alt="PRs welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen">
</p>

---

## ✨ Features
- ✅ **End-to-end pipeline**: load → clean → scale → train → evaluate  
- ✅ **Multiple models**: Logistic Regression, Random Forest, SVM  
- ✅ **Robust evaluation**: Accuracy, Precision, Recall, F1, Confusion Matrix  
- ✅ **Clear visuals** for distributions & correlations  
- ✅ **Notebook-first** workflow (easy to extend & demo)

---

## 🔍 How It Works
1. **Load data** (CSV) and validate schema  
2. **Preprocess**: fix invalid zeros, handle missingness, outlier sanity checks  
3. **Scale** numeric features (StandardScaler)  
4. **Train** baseline & tree-based models with sensible defaults  
5. **Evaluate** via holdout/CV + confusion matrix & classification report  
6. **Select** the best model for downstream predictions

---

## ⚙️ Quickstart

```bash
# 1) Clone
git clone https://github.com/ADDY-IN/Diabetes_Prediction_Model.git
cd Diabetes_Prediction_Model

# 2) (Optional) Create & activate venv
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

# 3) Install dependencies
pip install -r requirements.txt

# 4) Run the notebook
jupyter notebook main.ipynb
````

> Tip: If using VS Code, open the folder → select Python kernel → run cells top-to-bottom.

---

## 🚀 Roadmap

* 🔧 **Hyperparameter tuning** (Grid/Random/Bayes)
* 🌲 **Gradient boosting** (XGBoost/LightGBM/CatBoost)
* 🧮 **Calibration** (Platt/Isotonic) for better probability quality
* 🧠 **Explainability** (SHAP) to show feature impact
* 🌐 **Deploy** minimal API (FastAPI) + demo UI (Streamlit)

---

## 🤝 Contributing

* Fork → create feature branch → PR.
* Keep code cells tidy; prefer small, named functions for steps.
* Add/Update results in the **Metrics** table when improving models.

---

## 📫 Contact

Built by **Aditya Kaushik** • Open to feedback & PRs.
If this helped, ⭐ the repo!

```
