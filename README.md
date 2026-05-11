# 🌾 Smart Crop Recommendation System

This project helps farmers or users identify the most suitable crop to grow based on soil nutrients and environmental conditions.
Using Machine Learning algorithms, the system analyzes factors like nitrogen, phosphorus, potassium, temperature, humidity, pH, and rainfall to recommend the best crop.

The project was developed in Google Colab using Python and popular ML libraries.

---

## 📌 Features

* Crop prediction based on soil and weather conditions
* Data preprocessing and feature scaling
* Exploratory Data Analysis (EDA)
* Comparison of multiple ML models
* Automatic selection of the best-performing model
* Model saving using Joblib
* Ready for deployment in future web applications

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* Joblib
* Google Colab

---

## 📂 Dataset Information

The dataset was taken from Kaggle:

[Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset?utm_source=chatgpt.com)

### Dataset Contains:

* 2200 rows
* 22 crop categories
* 7 input features

### Input Features

* Nitrogen (N)
* Phosphorus (P)
* Potassium (K)
* Temperature
* Humidity
* pH
* Rainfall

---

## 📊 Exploratory Data Analysis

Some analysis performed in this project:

* Checking missing values
* Understanding data types
* Crop distribution visualization
* Correlation heatmap between features

The dataset was clean and did not contain any missing values.

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were used:

* Label Encoding for crop labels
* Train-Test Split
* Feature Scaling using `StandardScaler`

Training Data: 80%
Testing Data: 20%

---

## 🤖 Machine Learning Models Used

### 🌳 Random Forest Classifier

* Accuracy: **99.54%**

### ⚡ XGBoost Classifier

* Accuracy: **98.86%**

After comparison, the Random Forest model performed slightly better and was selected as the final model.

---

## 💾 Saved Model Files

The trained files are stored as:

```bash id="7xsh31"
crop_recommendation_model.pkl
crop_label_encoder.pkl
crop_scaler.pkl
```

These files can later be used for deployment or real-time prediction systems.

---

## 🧪 Sample Prediction

### Input

```python id="r83jdd"
N = 50
P = 30
K = 20
Temperature = 30.5
Humidity = 80
pH = 6.5
Rainfall = 200
```

### Predicted Output

```python id="32o9eu"
Recommended Crop: Coconut
```

---

## ▶️ Steps to Run the Project

### 1. Install Required Libraries

```bash id="0zjlwm"
pip install xgboost pandas scikit-learn seaborn matplotlib joblib
```

### 2. Upload Kaggle API File

Upload `kaggle.json` to access the dataset from Kaggle.

### 3. Run the Notebook

Execute all cells in the Colab notebook step by step.

---

## 📈 Project Workflow

```text id="w0e2b1"
Dataset Collection
        ↓
Data Analysis
        ↓
Preprocessing
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Best Model Selection
        ↓
Crop Prediction
```

---

## 🚀 Future Enhancements

* Create a Flask or Streamlit web application
* Add real-time weather API support
* Mobile application integration
* Deployment on cloud platforms
* Deep learning-based recommendation system

---

## 👩‍💻 Developed By

**Yeshaswini R**
---

## ⭐ GitHub

If you found this project useful, consider giving the repository a star ⭐
