# 🩸 Blood Transfusion Donation Prediction
Are you ready to use Machine Learning to predict life-saving blood donation behavior? Welcome to the Blood Transfusion ML Project, where we blend practical healthcare data with cutting-edge machine learning techniques to derive meaningful predictions.

📊 Project Overview
This project focuses on building and evaluating multiple machine learning models to predict whether an individual will donate blood. By analyzing past donation patterns and key features, we can model future donation likelihoods—critical for efficient blood bank inventory management and healthcare planning.

📁 Dataset
The dataset, blood.csv, contains anonymized donor information with features like:
Recency: Months since last donation
Frequency: Total number of donations
Monetary: Total blood donated
Time: Months since the first donation
Target: Whether they donated in the last campaign

🛠️ Tools & Libraries
pandas, matplotlib, seaborn – for data exploration and visualization
scikit-learn – for model building and evaluation
xgboost – for advanced gradient boosting techniques

🤖 Machine Learning Models Implemented
Model	Accuracy Achieved
Logistic Regression	76.67%
Random Forest	74.00%
Support Vector Machine	77.33%
Gradient Boosting	78.67% ✅

📌 Key Highlights
Data Preprocessing:
-Feature scaling using StandardScaler.
-Stratified train-test split (80-20).
Visualization:
-Heatmaps to understand correlation.
-Confusion matrices for performance intuition.
Error Handling:
-Encountered a label mismatch with XGBoost. The target labels were [1, 2] instead of [0, 1]—a subtle but crucial preprocessing fix!

🧠 Insights & Learnings
Tree-based models like Gradient Boosting tend to outperform linear models for this dataset.
Proper scaling improves model performance, especially for SVM.
Label encoding and data sanity checks are critical before model training (as we saw with XGBoost).

🚀 How to Run
Upload blood.csv to your runtime.
Open the notebook in Google Colab.
Run all cells sequentially. Dependencies will auto-install.
Check out the accuracy scores and performance plots at the end.

👩‍🔬 Built By
Diya Goswami
🔬 Enthusiast in AI for Healthcare
📘 3rd Year B.Tech CSE | Health Informatics
💡 Passionate about meaningful, data-driven projects
