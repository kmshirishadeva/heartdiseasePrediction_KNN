# ❤️ Heart Disease Prediction using KNN, Random Forest & Decision Tree

![Heart Disease Banner](https://github.com/kmshirishadeva/heartdiseasePrediction_KNN/blob/main/assets/heart-banner.png) <!-- Optional: Add your own banner or remove this line -->

## 🧠 Project Overview

This project applies **Machine Learning algorithms** to predict the likelihood of a patient developing **heart disease** based on clinical parameters. The goal is to support **early detection**, enable **timely intervention**, and assist healthcare professionals in **making better decisions**.

### 📊 Core Idea
By training models on structured health data, we assess a patient’s risk level using:
- 🔍 **K-Nearest Neighbors (KNN)**
- 🌲 **Decision Tree**
- 🌳 **Random Forest**

---

## 📈 Model Accuracy Comparison

| Algorithm              | Hyperparameters             | Accuracy     |
|------------------------|-----------------------------|--------------|
| 🔹 K-Nearest Neighbors | `k = 12`                    | **84.48%**   |
| 🌿 Decision Tree       | `max_depth = 3`             | **78.51%**   |
| 🌳 Random Forest       | `n_estimators = 90`         | **83.12%**   |

✅ **KNN** provided the best performance with `84.48%` accuracy.

---

## 📁 Dataset Used

- The dataset includes attributes such as:
  - Age, Sex, Chest Pain Type, Blood Pressure
  - Cholesterol, Resting ECG, Maximum Heart Rate
  - Exercise-Induced Angina, ST Depression, etc.

🗂 Source: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

---

## 🔍 How it Works

1. **Data Preprocessing**:
   - Handled missing values
   - Performed normalization/scaling
   - Encoded categorical values

2. **Model Building**:
   - Trained and evaluated KNN, Decision Tree, and Random Forest models
   - Fine-tuned hyperparameters using `GridSearchCV` and manual tuning

3. **Prediction**:
   - User inputs clinical data
   - Model returns risk level (likely / unlikely to have heart disease)

---

## 📊 Visualizations

- Correlation Heatmaps
- Model Performance Charts
- Feature Importance Graphs


---

## ⚙️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/kmshirishadeva/heartdiseasePrediction_KNN
   cd heartdiseasePrediction_KNN

2. pip install -r requirements.txt
3. jupyter notebook Heart_Disease_Prediction.ipynb

