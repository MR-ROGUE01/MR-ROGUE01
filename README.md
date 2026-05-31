<h1 align="center">Hey, I'm Raj (MR-ROGUE01) 👋</h1>
<h3 align="center">B.Tech CSE (AI & ML) · Amity University Jharkhand · Batch 2028</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-4DAACC?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
</p>

---

## 🧠 About Me

B.Tech CSE (AI & ML) undergraduate at Amity University Jharkhand **(CGPA: 7.97 / 10)**.

I build end-to-end ML pipelines and data workflows using Python, scikit-learn, pandas, and NumPy — from raw data cleaning and feature engineering to pipeline serialization and EDA.

- 🔬 Built a **Sleep Breathing Irregularity Detection** system using 1D CNN + LOPO cross-validation on real physiological signals
- 🚢 Built a fully **leakage-free Titanic survival prediction pipeline** deployed via Pickle
- 📊 Documenting my **100 Days of ML** — one concept, one notebook, daily
- 🎯 Open to **AI/ML and Data Science research internships**

---

## 🛠 Languages & Tools

**Languages**

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-e38c00?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

**ML / AI & Data Science**

<p align="left">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/1D%20CNN-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
</p>

**Data Visualization**

<p align="left">
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
</p>

**Developer Tools**

<p align="left">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Pickle-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>

**Core CS**

<p align="left">
  <img src="https://img.shields.io/badge/DSA-00599C?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/OOP-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/DBMS-e38c00?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Operating%20Systems-555555?style=for-the-badge&logo=linux&logoColor=white" />
</p>

---

## 🚀 Featured Projects

### 🫁 Sleep Breathing Irregularity Detection
> Python · scikit-learn · NumPy · SciPy · 1D CNN

Butterworth bandpass filter (0.17–0.4 Hz) on 8-hr overnight recordings from 5 participants → ~8,800 labeled 30-sec windows → 2-layer 1D CNN for 3-class classification (Normal / Hypopnea / Obstructive Apnea). LOPO cross-validation with per-fold StandardScaler and class-weight balancing. Evaluated via macro-F1, precision, recall, confusion matrix.

[View Repo →](https://github.com/MR-ROGUE01/sleep-breathing-irregularity-detection)

---

### 🚢 End-to-End Titanic Survival Pipeline
> Python · scikit-learn · pandas · Pickle

5-stage leakage-free `sklearn.Pipeline`: ColumnTransformer imputation → OneHotEncoder → MinMaxScaler → SelectKBest(chi², k=5) → DecisionTreeClassifier. Single `.fit()` / `.predict()` call. **63.9% mean CV accuracy (5-fold)**. Serialized via Pickle for one-line inference deployment.

[View Repo →](https://github.com/MR-ROGUE01/end-to-end-titanic-survival-pipeline)

---

### 🎬 Netflix Dataset: Data Cleaning & EDA
> Python · pandas · NumPy · matplotlib

Cleaned 6,234-record dataset: resolved 3,036 nulls across 5 columns, parsed mixed duration strings to `int64`, cast dates to `datetime64`. Aggregated country-level production, visualized 10-category rating distribution and longest movies per year (2008–2020).

[View Repo →](https://github.com/MR-ROGUE01/Netflix-Data-Cleaning-EDA)

---

### 📦 ML Data Preprocessing Series (30+ notebooks)
> Encoding · Scaling · Imputation · Feature Engineering

MinMaxScaler on Wine Dataset · One-Hot Encoding on Used Car Sales (8,128 rows, 32 brands) · Ordinal & Label Encoding · Random Sample Imputation · Missing Indicator · KBinsDiscretizer · FunctionTransformer · ColumnTransformer — all transformers fit on train split only to prevent leakage.

---

## ⚡ GitHub Analytics

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=MR-ROGUE01&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=MR-ROGUE01&theme=tokyonight" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=MR-ROGUE01&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=MR-ROGUE01&theme=tokyonight" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=MR-ROGUE01&theme=tokyonight" />
</p>

---

## 🔧 What I'm Building Right Now

- Completing **100 Days of ML** — one preprocessing / modeling concept per day with clean, public notebooks
- Deepening sklearn pipelines — adding GridSearchCV, RandomForest, and XGBoost wrappers
- Practicing **DSA in Python** — linked lists, trees, recursion, sorting
- Exploring advanced feature engineering — target encoding, feature interactions, PCA

---

## 🎯 Philosophy

> *"I don't chase speed. I build depth — and that compounds over time."*

---

## 🔗 Connect With Me

- **LinkedIn:** https://www.linkedin.com/in/raj-kumar-gupta-a705aa325
- **Portfolio:** http://raj-neon-matrix.vercel.app/
- **Email:** rajkrgupta8757299494@gmail.com

---

```
// I usually understand a concept only after breaking my code a few times 😄
```
