# 🧠 Stroke Prediction & Patient Segmentation Project

**CRISP-DM Based Data science Workflow**
**Patient Segmentation using K-Means Clustering (Stroke Dataset)**
## 👤 My Contribution
This repository contains my individual contribution to a larger group machine learning project focused on healthcare data analysis.

My role in the project was to implement K-Means clustering to segment patients into meaningful groups based on health and demographic features. This was done as part of an exploratory data analysis effort to uncover patterns in patient profiles without using the stroke outcome label.

## 🎯Project Context 
The broader group project involved analyzing a healthcare dataset to explore factors related to stroke risk. The dataset included patient demographic and medical information such as age, BMI, glucose levels, and cardiovascular conditions.

Within this project, different machine learning techniques were explored. My specific focus was on unsupervised learning (clustering).

## 📊 Objective of My Work
The goal of my contribution was to:
* Apply unsupervised learning to patient data
* Identify natural groupings of patients based on health indicators
* Interpret clusters for potential health risk segmentation

## ⚙️ Methodology
The following steps were performed in my clustering work:
* Selection of relevant numerical health features
* Feature scaling using StandardScaler
* Determining optimal number of clusters using the Elbow Method
* Validating clustering quality using Silhouette Score
* Training a K-Means clustering model (k = 4)

## 📌 Clustering Results
| Cluster | Risk Level | Priority |
|---|---|---|
| 0 | MODERATE-HIGH 🟠 | 2 |
| 1 | MODERATE 🟡 | 3 |
| 2 | LOW 🟢 | 4 |
| 3 | HIGH 🔴 | 1 |

## Key Features Influencing Clusters
* Age
* Hypertension
* Heart disease
* Average glucose level
* BMI
## 🧠 Key Insight
The clustering revealed distinct patient groupings that naturally separate higher-risk and lower-risk individuals based on underlying health conditions. This provides a simple way to explore hidden structure in the dataset without relying on labeled outcomes.

## 🛠️ Tools & Libraries
* Python
* Pandas
* Scikit-learn (KMeans, StandardScaler)
* Matplotlib / Seaborn

## File in this Repository
📁 [cluster_modelling.ipynb](notebooks/cluster_modelling.ipynb)

## 📄 Note
This repository contains only my individual contribution (K-Means clustering) from a larger group machine learning project.
## ## ⚙️ Installation & Setup
1. Clone the repository:

```bash
git clone <repo-url>
cd MLG382-CYO-PROJECT
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the web app:

```bash
python src/web_app.py
```

