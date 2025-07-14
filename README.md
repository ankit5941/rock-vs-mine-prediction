# rock-vs-mine-prediction
Predicts whether a sonar signal is from a rock or mine using machine learning
# 🧠 Rock vs Mine Prediction using Machine Learning

This machine learning project predicts whether a sonar signal is coming from a **rock** or a **mine**, using data collected from sonar returns bouncing off various objects in the ocean. The project was built and tested in **Google Colab** using Python.

---

## 📚 Dataset Used

- **Dataset Name:** Sonar Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))
- **Features:** 60 frequency-based numeric attributes
- **Target Variable:** `R` (Rock) or `M` (Mine)

---

## 🔍 Project Overview

- ✅ **Exploratory Data Analysis** (EDA) using pandas and seaborn  
- ✅ **Data Preprocessing** (label encoding, train-test split)
- ✅ **Model Training:** Logistic Regression
- ✅ **Model Evaluation:** Accuracy, Confusion Matrix, and Classification Report
- ✅ **Prediction Demo:** User can input custom data for prediction

---

## 🔢 Model Details

- **Algorithm Used:** Logistic Regression (from scikit-learn)
- **Train/Test Split:** 80% training, 20% testing
- **Accuracy:** Achieved around 78.8% on test data

---

## 📊 Results

- **Accuracy:** ~78.8%
- **Classification Report:** Precision, Recall, and F1-score for both classes (`Rock`, `Mine`)
- **Confusion Matrix:** 13 true positives, 10 true negatives (example values)

---

## ▶️ Run this Project

### 🔗 Run it in Google Colab:
Click the badge below to open and run it directly in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_SHARE_LINK_HERE)

---

## ⚙️ Requirements

To run locally, install the following libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
