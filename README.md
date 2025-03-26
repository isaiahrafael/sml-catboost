
# 🏡 House Hunter: Powered by CatBoost

This repo contains a Jupyter Notebook (`catboost.ipynb`) that walks you through predicting house prices using the Ames Housing dataset and CatBoost. It's designed to be simple, readable, and easy to tweak. You’ll find everything from data preparation and model training to evaluation and some light tuning.

---

## 🚀 What It Does

- **Loads and Cleans the Dataset:**  
  Reads the Ames Housing data, handles missing values, and properly converts categorical features for CatBoost.

- **Trains a Regression Model:**  
  Uses CatBoost to build a regression model for predicting house prices.

- **Evaluates Model Performance:**  
  Calculates metrics like RMSE and R², and visualizes predictions versus actual values.

- **Displays Feature Importance:**  
  Highlights which features drive the predictions most, giving insights into the model.

- **Optional Tuning:**  
  Includes optional code to adjust key parameters for even better performance.

---

## 🛠 How to Set It Up

### 1. Clone the Repo
```
git clone https://github.com/isaiahrafael/sml-catboost.git
cd sml-catboost
```

### 2. Create a Virtual Environment (Recommended)
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scriptsctivate
```

### 3. Install Dependencies
If you have a `requirements.txt`:
```
pip install -r requirements.txt
```
Otherwise, install the following packages:
```
pip install catboost pandas numpy scikit-learn matplotlib seaborn
```

---

## ▶️ How to Run It

1. **Open the Notebook:**
   ```
   jupyter notebook catboost.ipynb
   ```
2. **Run Each Cell:**  
   Follow along step-by-step. Make sure your dataset (typically `train.csv` from Kaggle's House Prices competition) is in the same folder.

---

## 📦 Additional Notes

- **Dataset:**  
  You can download the Ames Housing dataset from [Kaggle - House Prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

- **In-Notebook Explanations:**  
  The notebook includes detailed comments on:
  - Why we use CatBoost Pools.
  - The importance of feature importance.
  - How early stopping and hyperparameters affect training.

- **Model Simplicity & Accuracy:**  
  The model is straightforward to interpret while still achieving good performance.

---

## 🧪 Optional Extras

- **Hyperparameter Tuning:**  
  Try adjusting `learning_rate`, `depth`, and `iterations` to see how the model performance changes.
  
- **Automated Tuning:**  
  Use CatBoost’s built-in `grid_search()` for automated hyperparameter tuning if you have more time.

- **Log-Transforming the Target:**  
  Consider applying a log transformation to `SalePrice` to stabilize variance and potentially improve results.

---
