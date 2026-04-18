# 🧠 AI Deepfake Detection using Metadata

## 📌 Overview
This project focuses on detecting deepfake media using **metadata-based features** instead of raw images or videos. The goal is to build lightweight machine learning models that classify media as real or fake using extracted metadata attributes.

---

## 🎯 Objective
- Detect whether a media file is **Real or Fake**
- Use structured **metadata features** instead of deep learning
- Compare multiple machine learning models for performance

---

## 📂 Dataset Source
The dataset used in this project is obtained from **Kaggle**.

- 📌 Source: Kaggle Deepfake Detection Metadata Dataset  
- 📊 Size: 1000 records  
- 🧾 Type: Synthetic metadata-based dataset for classification

This dataset contains structured metadata features extracted from media files to simulate deepfake detection scenarios.

---

## ⚠️ Note on Dataset
This dataset is **synthetically generated / simplified**, which leads to very high model performance.

In real-world scenarios:
- Data is noisy and imbalanced  
- Features are not perfectly separable  
- Deep learning models are often required for better accuracy  

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  

---

## 🔍 Project Workflow

### 1. Data Preprocessing
- Handled missing values in `generation_method`
- Encoded categorical variables using Label Encoding
- Dropped unnecessary column (`media_id`)

### 2. Exploratory Data Analysis
- Visualized class distribution (Real vs Fake)
- Analyzed media type distribution
- Generated correlation heatmap

### 3. Model Building
Implemented machine learning models:
- Logistic Regression  
- Random Forest  
- XGBoost  

### 4. Model Evaluation
- Accuracy Score  
- Confusion Matrix  
- Classification Report  
- Feature Importance Analysis  

---

## 📊 Results

| Model               | Accuracy |
|--------------------|---------|
| Logistic Regression| 1.00    |
| Random Forest      | 1.00    |
| XGBoost            | 1.00    |

---

## ⚠️ Important Observation
All models achieved **100% accuracy**, which may indicate:
- Highly separable dataset  
- Synthetic data structure  
- Possible feature leakage  

👉 In real-world applications, deepfake detection is significantly more complex.

---

## 📈 Key Features Contributing to Prediction
- Visual Artifacts Score  
- Lip Sync Score  
- Lighting Inconsistency Score  
- Compression Level  

---

## 🚀 Future Improvements
- Use real-world deepfake datasets (images/videos)
- Apply deep learning models (CNN, LSTM)
- Combine metadata + visual features
- Deploy as a web application

---

## 💡 Key Learning
- Metadata can be useful for lightweight ML models
- Importance of proper dataset evaluation
- High accuracy does not always mean real-world effectiveness

---

