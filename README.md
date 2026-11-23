# Assignment 2 – Machine Learning for Cybersecurity

## 📌 Overview

This assignment focuses on applying Machine Learning techniques to cybersecurity using login activity data. The main objective is to identify suspicious login behaviour and detect unusual activities using supervised and unsupervised learning techniques.

## 🎯 Objectives

- Analyze login activity data.
- Identify normal and suspicious login patterns.
- Apply Decision Tree Classification.
- Perform K-Means Clustering.
- Analyze feature importance.
- Predict suspicious activities using new records.
- Explore unsupervised anomaly detection techniques.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 📂 Dataset

**Dataset Name:** `simple_login_activity.csv`

The dataset contains login activity information with the following features:

| Feature | Description |
|---|---|
| record_id | Unique record identifier |
| failed_logins | Number of failed login attempts |
| login_hour | Hour of login |
| new_device | Indicates whether a new device was used |
| download_mb | Amount of downloaded data |
| label | Normal or Suspicious activity |

## 🤖 Algorithms Implemented

### 1. Decision Tree Classification

A supervised Machine Learning algorithm used to classify login activities into:
- Normal
- Suspicious

### 2. K-Means Clustering

An unsupervised learning algorithm used to group similar login activities into two clusters.

### 3. Feature Importance Analysis

Identifies which login features contribute most to the Decision Tree's predictions.

### 4. Anomaly Detection – Preprocessing

The notebook also includes preprocessing for unsupervised anomaly detection using:
- K-Means
- DBSCAN
- Isolation Forest
- PCA

## ⚙️ Project Workflow

1. Import required libraries.
2. Upload the login activity dataset.
3. Explore the dataset.
4. Handle missing values and duplicate records.
5. Select important features.
6. Split the data into training and testing sets.
7. Train the Decision Tree model.
8. Evaluate model predictions.
9. Apply K-Means clustering.
10. Analyze feature importance.
11. Predict new login activities.
12. Save the final results as a CSV file.

## 📊 Model Evaluation

The Decision Tree model is evaluated using:
- Accuracy Score
- Confusion Matrix
- Actual vs Predicted Values

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

2. Open Google Colab.

3. Upload `assignment2.ipynb`.

4. Upload `simple_login_activity.csv`.

5. Run all cells sequentially.

## 📁 Repository Structure

```text
Assignment-2/
│
├── assignment2.ipynb
├── simple_login_activity.csv
├── Lab2_Login_ML_Result.csv
└── README.md
```

## 🏁 Conclusion

This assignment demonstrates how Machine Learning can help identify suspicious login activities and analyze unusual user behaviour.

Decision Tree Classification is used for predicting login activity labels, while K-Means Clustering helps identify groups with similar characteristics.

The project provides practical experience in applying Machine Learning techniques to cybersecurity problems.

---

**Author:** Aryaveer Singh

**Domain:** Machine Learning | Cybersecurity

**Platform:** Google Colab
