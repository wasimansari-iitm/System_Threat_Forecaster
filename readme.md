## System Threat Forecaster

A machine learning project aimed at forecasting system threats by analyzing historical threat data and identifying patterns using classification techniques. This notebook is developed as part of the **IIT Madras Data Science Diploma**.

---

## 📌 Project Overview

This project involves:

- Loading and preprocessing system threat data.
- Performing exploratory data analysis (EDA).
- Building classification models to predict the type of system threat.
- Evaluating model performance using accuracy and classification metrics.

The core focus is on **predicting cyber threats** using machine learning models trained on features like CPU load, memory usage, packet loss, and more.

---

## 🔍 Dataset

The dataset used in this project contains records of system status and known threat categories. It includes the following features:

- `OSVersion`, `Location`, `IsAGamer`, `SignatureID`, etc.
- Label indicating prediction of being infected.

> **Note:** Due to file size, the dataset (`train.csv`) exceeds GitHub's 50MB upload limit. It's recommended to use [Git LFS](https://git-lfs.github.com/) if you want to track this file.

---

## 📊 Models Used

- **Logistic Regression**
- **Stochastic Gradient Descent Classifier**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **XGBoost Classifier**

The model performance was evaluated using accuracy score and classification reports. Feature importance and confusion matrices were visualized to better understand model behavior.

---

## 📈 Results

- Best performing model: `XGBoost Classifier`
- Accuracy: *[to be filled after training]*
- Insights from feature importance and confusion matrix are visualized in the notebook.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/wasimansari-iitm/System_Threat_Forecaster.git
   cd System_Threat_Forecaster
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook 24ds3000090-notebook-t12025.ipynb
   ```

---

## 🧠 Skills Demonstrated

- Data preprocessing and EDA
- Model selection and hyperparameter tuning
- Evaluation metrics and visualization
- Handling large datasets (recommendation to use Git LFS)

---

## 📚 Acknowledgments

This project is developed by **Wasim Ansari** as part of the **Data Science Diploma Program** by **IIT Madras**.

---

## 🛠️ Future Work

- Integrate real-time threat detection API
- Use LSTM/Transformer models for time-series threat prediction
- Optimize for deployment in enterprise environments

---