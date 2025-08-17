# Bitcoin Fraud & Money Laundering Detection 

**Bitcoin Fraud Detection: XGBoost + Network Analysis**  
My data science bootcamp capstone project.  
Detecting fraudulent Bitcoin transactions using machine learning and graph network analysis.

---

## 📊 Results

- **F1 Score**: 0.779  
- **ROC AUC**: 0.977  
- **Algorithm**: XGBoost Classifier + Network Analysis  
- **High Risk Detected**: 7,249 transactions (>80% fraud probability)

---

## 🚀 Project Overview

This project combines advanced machine learning with network graph analysis to detect Bitcoin fraud using the Elliptic Dataset.  
Built a comprehensive risk assessment system for **203K+ Bitcoin transactions**.

**Key Features:**
- XGBoost classification with class imbalance handling  
- Network graph analysis for suspicious connections  
- Risk scoring system for unknown transactions  
- Statistical feature importance analysis  
- Real-time fraud probability assessment  

---

## 📈 Methodology

### Data Exploration & Preprocessing
- Elliptic Dataset: 203,769 transactions with 166 features  
- RobustScaler for handling Bitcoin whale transactions  
- Feature engineering: 94 local + 72 aggregated features  
- Class distribution: 2.2% illicit, 20.6% licit, 77.1% unknown  

### Model Development
- XGBoost with optimal hyperparameters (max_depth=8, n_estimators=500)  
- Class imbalance handling with scale_pos_weight=9.25  
- 5-fold cross-validation for robust evaluation  
- GridSearchCV for hyperparameter optimization  

### Network Analysis
- Graph connectivity analysis using NetworkX  
- Risk propagation through Bitcoin transaction network  
- Neighbor transaction risk assessment  
- Suspicious cluster identification  

### Risk Assessment System
- 4-tier risk categorization (Safe / Low / Medium / High)  
- Unknown transaction probability scoring  
- Export functionality for investigation teams  

---

## 🎯 Key Learnings
- Feature engineering crucial → aggregated neighbor features most predictive  
- Network effects reveal 21.8% risk propagation to connected transactions  
- Class imbalance requires weighted sampling for minority fraud detection  
- Graph analysis enhances traditional ML predictions significantly  

---

## 🔗 Links
- [Kaggle Notebook: Bitcoin Fraud Detection (XGBoost & Network Analysis)](https://www.kaggle.com/code/oxspaceman/bitcoin-fraud-money-laundering-detection)
- [Dataset: Elliptic Bitcoin Dataset](https://www.kaggle.com/ellipticco/elliptic-data-set)

---

## 🚀 Future Improvements
- Real-time transaction monitoring system  
- Deep learning with Graph Neural Networks (GNN)  
- Temporal pattern analysis over time  
- Multi-cryptocurrency fraud detection  
- API development for production deployment  

---

## 📝 About
This is my final project from data science bootcamp.  
I used machine learning and network analysis to catch Bitcoin fraud transactions and uncover money laundering networks used by organized crime groups – a real problem in cryptocurrency world.  

**Status**: Completed ✅  
**Score**: ROC AUC: 0.977  
**Impact**: 157K+ transactions risk-assessed, 7,249 high-risk flagged

