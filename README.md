# 🫀 Heart Disease Analysis using NumPy, Pandas, Matplotlib & Seaborn

This project explores the **Heart Disease UCI dataset** using data analysis and visualization techniques. No machine learning models are used — instead, we use exploratory data analysis (EDA) to understand key patterns that relate to heart disease.

---

## 📁 Dataset Details

- **Source**: [Kaggle - Heart Disease UCI](https://www.kaggle.com/ronitf/heart-disease-uci)
- **Records**: 303
- **Features**: 13 input features + 1 target (heart disease presence)

### 🧾 Target Variable
- `0`: No heart disease  
- `1`: Heart disease

---

## 🔧 Tools Used

| Tool          | Purpose                         |
|---------------|----------------------------------|
| **NumPy**     | Basic statistics and calculations |
| **Pandas**    | Data loading and exploration     |
| **Matplotlib**| Basic visualizations             |
| **Seaborn**   | Beautiful, insightful charts     |

---

## 🔍 Exploratory Data Analysis (EDA)

### ✅ Target Distribution
Bar plot showing how many people have or don’t have heart disease.

### ✅ Correlation Heatmap
Heatmap showing correlation between features like:
- `thalach` (max heart rate) – negatively correlated
- `cp` (chest pain type) – positively related

### ✅ Feature Histograms
Histograms for age, cholesterol, heart rate, etc.

### ✅ Boxplots
Compared cholesterol and resting blood pressure across target classes.

### ✅ Pairplot
Visual patterns between important features (e.g., age vs heart rate).

---

## 📊 NumPy Statistics Example (on `chol` column)

```python
Mean:     ~246 mg/dL
Median:   ~240 mg/dL
Std Dev:  ~51
25th %:   ~211
75th %:   ~275
