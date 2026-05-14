# Website Phishing Detection

**Machine Learning Classification Project** | Detecting phishing websites to enhance cybersecurity and protect users from online fraud.

## 📋 Project Overview
This project builds accurate classification models to identify phishing (malicious) websites versus legitimate ones. By analyzing website characteristics and URL features, the models can help security systems flag suspicious sites in real-time and reduce the risk of users falling victim to phishing attacks.

## 🎯 Business / Real-World Problem
Phishing remains one of the most common and damaging cyber threats. Early and accurate detection allows organizations and security tools to block fraudulent websites, protecting users and reducing financial and reputational damage.

## 🗂️ Dataset
- **Source**: Phishing website dataset (loaded from AWS S3)
- **Target**: Binary classification (`phishing` vs `legitimate`)
- **Features**: URL-based characteristics, domain info, page content features, SSL certificate details, traffic statistics, and other website metadata.

## 🔧 Key Techniques & Models
- **Data Preprocessing**: Feature engineering, handling categorical variables, scaling
- **Exploratory Data Analysis**: Feature distribution analysis and correlation studies
- **Modeling**:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting
  - XGBoost, LightGBM, CatBoost
  - Other classifiers (SVM, KNN, etc.)
- **Advanced Techniques**: Hyperparameter tuning, feature importance analysis, model comparison using multiple metrics (Accuracy, Precision, Recall, F1-score, ROC-AUC)

## 📊 Results
- Achieved strong classification performance using ensemble tree-based models
- Identified the most predictive features for distinguishing phishing sites
- Focused on high **Recall** to minimize false negatives (missing actual phishing sites)

## 📄 Reports
- [Full Project Report (PDF)](Website%20Phishing%20Detection/Reports/Website%20Phishing%20Detection%20Report.pdf)
- [Presentation Slides (PDF)](Website%20Phishing%20Detection/Reports/Website%20Phishing%20Detection%20Slides.pdf)

## 🛠️ Technologies Used
**Python** • **pandas** • **scikit-learn** • **XGBoost** • **LightGBM** • **CatBoost** • **Matplotlib** • **Seaborn**
