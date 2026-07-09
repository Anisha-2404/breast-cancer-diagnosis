#  Breast Cancer Prediction using Random Forest

A Machine Learning project that predicts whether a breast tumor is **Malignant (Cancerous)** or **Benign (Non-Cancerous)** using the **Random Forest Classifier**. The project uses a breast cancer dataset from Kaggle and demonstrates the complete machine learning workflow, including data preprocessing, model training, evaluation, and model saving.

---

## 📌 Project Overview

Breast cancer is one of the most common cancers worldwide. Early detection plays a vital role in improving treatment outcomes. This project builds a Random Forest Classification model to predict whether a tumor is malignant or benign based on various medical measurements.

---

## 🎯 Objective

- Predict whether a breast tumor is:
  - **Malignant (M)** – Cancerous
  - **Benign (B)** – Non-Cancerous
- Learn the end-to-end machine learning workflow using Random Forest.

---

## 📂 Dataset

- **Dataset:** Breast Cancer Dataset
- **Source:** Kaggle

### Target Variable

| Value | Meaning |
|-------|---------|
| M | Malignant (Cancerous) |
| B | Benign (Non-Cancerous) |

After preprocessing:

| Value | Meaning |
|-------|---------|
| 1 | Malignant |
| 0 | Benign |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Google Colab

---

## 📊 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Explore Dataset
4. Check Missing Values
5. Remove Duplicate Records
6. Encode Target Variable
7. Feature Selection
8. Train-Test Split
9. Data Preprocessing using Pipeline
10. Train Random Forest Classifier
11. Make Predictions
12. Evaluate Model Accuracy
13. Save Trained Model (.pkl)
14. Download Saved Model

---

## 🤖 Model Used

**Random Forest Classifier**

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## 📈 Evaluation Metrics

- Accuracy Score
- Classification Report
- Confusion Matrix
- ROC-AUC Score

---

## 📁 Project Structure

```
Breast-Cancer-Prediction-Random-Forest/
│
├── Breast_Cancer_Random_Forest.ipynb
├── breast-cancer.csv
├── breast_cancer_random_forest_model.pkl
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Breast-Cancer-Prediction-Random-Forest.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

or upload it to **Google Colab**.

4. Run all cells.

---

## 📌 Sample Prediction

| Radius | Texture | Area | Prediction |
|---------|----------|------|------------|
| 17.9 | 10.3 | 1001 | Malignant |
| 12.5 | 16.2 | 520 | Benign |

---

## 💾 Model Saving

The trained model is saved using **Joblib**.

```python
joblib.dump(model, "breast_cancer_random_forest_model.pkl")
```

The saved model can later be loaded using:

```python
model = joblib.load("breast_cancer_random_forest_model.pkl")
```

---

## 📚 Learning Outcomes

- Data preprocessing
- Handling missing values
- Feature engineering
- Data splitting
- Machine Learning with Random Forest
- Model evaluation
- Model serialization using Joblib

---

## 👩‍💻 Author

**Anisha Jain**

MCA Student | Aspiring Data Analyst

---

⭐ If you found this project useful, consider giving it a star!
