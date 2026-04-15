💳 Credit Card transaction Fraud Detection System
📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Fraud detection is a critical problem in the banking and financial services industry, where even a small percentage of fraudulent transactions can lead to significant financial losses.
The objective of this project is to build a predictive model that can accurately identify fraudulent transactions while minimizing false negatives.
🎯 Problem Statement
Credit card fraud detection involves identifying rare fraudulent transactions from a highly imbalanced dataset. The challenge lies in detecting fraud cases (minority class) without misclassifying legitimate transactions.
📊 Dataset

* Source: Kaggle Credit Card Fraud Detection Dataset
* Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
* Total Transactions: 284,807
* Fraud Cases: 492 (~0.17%)
⚠️ Note: The dataset is not included in this repository due to its large size. Please download it from the link above.
🛠️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Matplotlib, Seaborn
⚙️ Project Workflow
1. Data Preprocessing

* Loaded and explored dataset
* Checked for missing values
* Scaled 'Time' and 'Amount' features
2. Handling Imbalanced Data

* Applied SMOTE (Synthetic Minority Oversampling Technique)
* Balanced fraud and non-fraud classes
3. Model Building

* Logistic Regression model used for classification
* Trained on balanced dataset
4. Model Evaluation

* Confusion Matrix
* Classification Report
* ROC Curve
📈 Key Visualizations

* Fraud vs Normal Transaction Distribution
* Transaction Amount Distribution
* Confusion Matrix Heatmap
* ROC Curve
🧠 Key Insights

* The dataset is highly imbalanced, making accuracy an unreliable metric
* Recall is prioritized to minimize false negatives (missed fraud cases)
* SMOTE improves the model’s ability to detect fraud by balancing the dataset
* Fraud detection systems must focus on early detection to reduce financial risk
📊 Model Performance (Example)

* High Recall for fraud detection
* Improved detection of minority class after applying SMOTE
💼 Business Impact

* Helps identify fraudulent transactions in real-time
* Reduces financial losses for banks
* Improves customer trust and security
* Supports risk management systems in financial institutions
🚀 Future Improvements

* Use advanced models like Random Forest, XGBoost
* Implement real-time fraud detection pipeline
* Deploy as a web application using Flask
* Integrate with Power BI for dashboard visualization
📂 Project Structure

```
Fraud-Detection/
│── fraud_detection.ipynb
│── README.md

```

👤 Author

* Sakshi
* Aspiring Data Analyst / Data Scientist
