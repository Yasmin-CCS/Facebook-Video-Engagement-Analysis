# 📊 Facebook Video Engagement Analysis

## 🧠 Overview
This project analyzes Facebook post engagement to determine whether videos still outperform other content types.

---

## 🟡 Situation
A company using Facebook for digital marketing lacked clear insights into the performance of video content. This gap limited their ability to plan campaigns effectively.

## 🔴 Complication
Without a reliable method to evaluate engagement, the team risked misclassifying content types, which could lead to poor targeting and inefficient resource allocation.

## 🟢 Action
- Explored multiple machine learning approaches to model post engagement, including full-dataset and cluster-specific analyses.
- Applied **Principal Component Analysis (PCA)** to reduce dimensionality and reveal hidden patterns.
- Performed **clustering** to isolate distinct behavioral groups.
- Trained and compared several models; found that **logistic regression within a high-engagement cluster** achieved the best performance, minimizing false positives and improving precision.

## 🟢 Result
- Identified a specific cluster strongly associated with video content engagement.
- The final logistic regression model on that cluster achieved the **highest AUC** across all models tested.
- Delivered actionable insights for **targeted content planning**, allowing the team to make data-driven decisions without needing to generalize across a highly heterogeneous dataset.

---

## 🛠 Tools & Techniques
- Python (pandas, scikit-learn, matplotlib)
- PCA
- K-means clustering
- Logistic Regression
- ROC Curve / AUC for model evaluation

---

## 📌 Key Insight
Videos consistently outperformed other content types across most engagement metrics — including reactions, comments, and shares — and showed a **higher overall engagement**. However, segmenting the audience via clustering was essential to accurately capturing this pattern and minimizing noise from non-representative data.
