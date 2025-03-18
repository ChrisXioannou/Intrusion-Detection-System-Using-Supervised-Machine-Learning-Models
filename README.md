# Intrusion Detection System Using Supervised Machine Learning Models

This repository contains my **research thesis and Google Colab code** for training **supervised machine learning models** on the **KDD Cup 1999 dataset** to improve **intrusion detection in cybersecurity**. The study evaluates **binary vs. multi-class classification, feature selection, and performance optimization** to enhance Intrusion Detection Systems (IDS).

📄 **Thesis Link:** [View the full research here](https://doi.org/10.5281/zenodo.15040140)

## 🔍 **Abstract**
The growing complexity of cyber threats has necessitated the development of **innovative solutions** to protect modern networks. **Intrusion Detection Systems (IDS)** have long been a cornerstone of cybersecurity, designed to monitor and detect **anomalous activities**. However, they are often associated with **moderate detection accuracy and high false alarm rates**, particularly when encountering complex or novel attack patterns. This underscores the need for **further experimentation and refinement**.

This research explores the application of **machine learning algorithms for intrusion detection** using the **KDD Cup 1999 dataset**, aiming to classify network traffic into different categories, distinguishing between **normal activity and various types of malicious threats**. In addition to evaluating **multi-class classification**, a **binary classification approach** was also examined to determine whether simplifying the detection process improves overall reliability.

These insights emphasize the importance of **selecting models based on IDS deployment needs**. Additionally, this study highlights key challenges such as **high false positive rates, imbalanced class distributions, and the necessity for continuous adaptation** in cybersecurity. Addressing these issues is crucial for developing **adaptive and proactive network security strategies**, strengthening the role of **machine learning in modern IDS implementations**.

## 🖥️ **Code Overview**
The code provided in this repository enables users to train and evaluate supervised machine learning models for intrusion detection. The models were tested on the KDD Cup 1999 dataset with a focus on:
 - Feature Selection & Engineering
 - Binary vs. Multi-Class Classification
 - Performance Metrics & Model Comparisons

The research aims to improve detection accuracy while reducing false positives, providing insights into the best models for different IDS deployment scenarios

## 📊 **Machine Learning Models Used**
This study evaluates and compares multiple supervised learning algorithms:
 - 🌲 Random Forest – Robust tree-based classifier, effective in feature importance analysis.
 - 🔍 k-Nearest Neighbors (KNN) – Excels in anomaly detection with minimal false alarms.
 - 📈 Logistic Regression – Linear model for classification, suitable for detecting general patterns.
 - 🚀 XGBoost – Optimized gradient boosting model for improved classification performance.
 - 📊 Naïve Bayes – A probabilistic classifier useful for handling categorical data.

Each model was fine-tuned using RandomizedSearchCV and k-fold cross-validation, ensuring optimal performance in detecting cyber threats.

## 📂 **Project Structure & How to Use the Code**
The repository contains Jupyter Notebooks that guide you through training and evaluating Intrusion Detection Models. Make sure to update the path variables to match your directory structure before running the code.

📌 **Notebooks Available**
 - 📄 **MultiClass_Classification.ipynb**
Implements multi-class classification, categorizing network traffic into Normal, DoS, Probe, R2L, and U2R attack types. This approach is more detailed but comes with higher computational costs and class imbalance challenges.

 - 📄 **Binary_Classification.ipynb**
Contains the code for training binary classification models, distinguishing between normal traffic and attacks. This notebook explores false positive rates, detection accuracy, and model comparisons for a simplified intrusion detection approach.

🔗 Dataset & Configuration
You can download the full KDD Cup 1999 dataset used in this research here:

**Dataset Link:** [View the full Dataset here](https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)

## 📢 **Contribute & Support**
🌟 If you find this project useful, please star ⭐ this repository!
👥 Contributions, issues, and feature requests are welcome!
