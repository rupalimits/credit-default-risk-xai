# Credit Default Risk Prediction with Explainable AI

This project predicts the probability of loan default using the [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk) dataset.  
It combines advanced machine learning models with Explainable AI (XAI) techniques to ensure transparency in credit decision-making — a critical requirement in modern lending.

---

## 🚀 Project Overview
- **Goal:** Predict loan default probability to support responsible lending decisions.
- **Dataset:** Home Credit Default Risk (Kaggle)
- **Tech Stack:** Python, LightGBM, XGBoost, SHAP, Pandas, NumPy, Matplotlib, Seaborn
- **Key Features:**
  - Behavioral, demographic, and credit history feature engineering
  - Model training & optimization (LightGBM, XGBoost)
  - Explainable AI with SHAP for transparent loan decisioning
  - Scalable ML pipeline design for production readiness

---

## 📊 Current Progress
- ✅ Repository initialized  
- ✅ Project structure defined  
- 🔄 Data sourcing and preprocessing pipeline in progress  
- 🔄 Model training and evaluation to follow  
- 🔄 SHAP-based model interpretation planned  
- 🔄 Deployment simulation (FastAPI + Docker) planned  

---

## 📈 Expected Outcome
- **Model Performance:** Targeting ~0.76 AUC (based on industry benchmarks for this dataset)
- **Transparency:** Feature-level explanations for each credit risk prediction
- **Impact:** Demonstrates ability to design scalable, interpretable ML solutions for credit risk

---

## 📂 Repository Structure
## 📂 Repository Structure
```plaintext
credit-default-risk-xai/
│
├── README.md                  # Project overview and documentation
├── data/                       # Data files or links (placeholder)
│   └── .gitkeep
├── notebooks/                  # Jupyter notebooks for EDA, modeling, explainability
│   └── .gitkeep
├── src/                        # Python scripts for modular pipeline
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── explainability.py
│   └── utils.py
├── requirements.txt            # Python dependencies
└── LICENSE                     # License file (MIT)

```
---

## 📦 Installation
1. **Clone the repository:**
```bash
git clone https://github.com/<your-username>/credit-default-risk-xai.git
cd credit-default-risk-xai
```

2. Install dependencies:
pip install -r requirements.txt

## 📁 Data Access
The dataset can be downloaded from Kaggle Home Credit Default Risk.
After downloading, place the CSV files in the data/ folder.

## 🛠 Planned Pipeline
- Data Preprocessing: Cleaning, handling missing values, encoding categorical features, feature scaling.
- Feature Engineering: Behavioral metrics, rolling transaction averages, credit utilization ratios.
- Model Training: Train multiple classifiers (LightGBM, XGBoost) and compare performance.
- Explainability: Use SHAP values for global and local interpretability.
- Deployment Simulation: Serve predictions via FastAPI and containerize with Docker.
- Monitoring: Add model drift detection and performance tracking.

## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to check the issues page.

## 👤 Author
Rupali Patel
GitHub: @rupalimits
