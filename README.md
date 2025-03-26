# 🏡 House Hunter: Powered by CatBoost

This repo contains a Jupyter Notebook (`catboost.ipynb`) that walks through predicting house prices using the Ames Housing dataset and CatBoost. It's designed to be simple, readable, and easy to tweak. You’ll find everything from data prep to training, evaluation, and some light tuning.

---

## 🚀 What It Does

- **Loads and cleans the Ames Housing dataset**
- **Converts categorical features properly for CatBoost**
- **Trains a regression model using CatBoost**
- **Evaluates it using RMSE and R²**
- **Visualises predictions and feature importance**
- **(Optionally) Tunes key parameters for better accuracy**

---

## 🛠 How to Set It Up

### 1. Clone the repo:
```bash
git clone https://github.com/isaiahrafael/sml-catboost.git
cd your-repo
2. (Recommended) Create a virtual environment:
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
3. Install dependencies:
pip install -r requirements.txt
If you don’t have a requirements.txt, just run:

pip install catboost pandas numpy scikit-learn matplotlib seaborn
▶️ How to Run It

jupyter notebook catboost.ipynb
Run each cell step-by-step.
Make sure your dataset (usually train.csv from Kaggle) is in the same folder.
📦 Notes

You can grab the dataset from Kaggle - House Prices
The notebook includes comments explaining:
Why we use Pool
Why feature importance matters
How early stopping and hyperparameters affect training
The model is simple enough to interpret, and accurate enough to be useful
🧪 Optional Extras

Try adjusting learning_rate, depth, and iterations for better performance
Use CatBoost’s built-in grid_search() if you have more time
You can log-transform SalePrice to improve results
Let me know if you run into anything or want to improve it further!