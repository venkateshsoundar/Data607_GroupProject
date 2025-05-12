# Estimation of Obesity Levels Based on Lifestyle and Dietary Patterns

A multi-class classification analysis to predict individual obesity levels using lifestyle, dietary, and demographic features. This project covers data ingestion, exploratory analysis, feature engineering, and evaluation of various machine learning models, including KNN, Decision Trees, SVM, Random Forests, and XGBoost, as well as binary classification experiments.

---

## 👥 Team Members
- Ayush Senthil Nelli  
- Hritvik Gaind  
- Satyam Kapoor  
- Venkateshwaran Balu Soundararajan  

---

## 📁 Repository Structure

```
├── data/
│   ├── raw/                       ← original survey CSV files
│   └── processed/                 ← cleaned and engineered datasets
│
├── notebooks/
│   └── Data607_GroupProject_Report.ipynb   ← full analysis notebook
│
├── scripts/
│   ├── data_preprocessing.py      ← cleaning and feature engineering
│   ├── eda_visualization.py       ← exploratory plots and summaries
│   └── model_training.py          ← training and evaluation routines
│
├── outputs/
│   ├── figures/                   ← static images and charts
│   └── model_reports/             ← performance metrics and logs
│
├── requirements.txt               ← project dependencies
└── README.md                      ← this file
```

---

## 🛠️ Setup & Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/venkateshsoundar/obesity-level-estimation.git
   cd obesity-level-estimation
   ```

2. **Create & activate** a Python environment  
   ```bash
   python3 -m venv venv
   source venv/bin/activate    # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. **Install** dependencies  
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch** the Jupyter notebook  
   ```bash
   jupyter notebook notebooks/Data607_GroupProject_Report.ipynb
   ```

---

## 🔍 Project Overview

Obesity is a growing global health concern linked to lifestyle and dietary factors. This analysis aims to:

- Examine relationships between demographic, lifestyle (activity levels, sleep quality), and dietary patterns (meals per day, caloric intake) with obesity categories.  
- Compare multi-class classification models (KNN, Decision Trees, SVM, Random Forests, XGBoost) to identify the most accurate predictor of obesity levels.  
- Conduct binary classification to distinguish obese vs. non-obese individuals and visualize decision boundaries.

---

## 📊 Data & Methodology

1. **Dataset Description**  
   - Source: Public survey data on lifestyle and dietary habits.  
   - Features include age, gender, meal frequency, caloric intake, activity level, water intake, alcohol consumption, caloric density, and more.

2. **Data Preprocessing**  
   - Handle missing values and outliers  
   - Encode categorical variables and scale numerical features  
   - Check and address multicollinearity

3. **Exploratory Data Analysis (EDA)**  
   - Descriptive statistics and distributions  
   - Correlation heatmaps and pair plots  
   - Obesity level breakdown by demographics

4. **Modeling**  
   - Multi-class classification with hyperparameter tuning  
   - Binary classification experiments (obese vs. non-obese)  
   - Evaluate using accuracy, precision, recall, F1-score, and ROC-AUC

---

## 📈 Key Findings

- **Top Model:** XGBoost achieved the highest multi-class accuracy (~XX%).  
- **Important Features:** Caloric density, physical activity level, and water intake were consistently strong predictors.  
- **Binary Classification:** Random Forest reached an ROC-AUC of ~YY% when distinguishing obese vs. non-obese.

---

## 🔮 Future Scope

- Incorporate additional lifestyle factors (sleep quality, stress levels).  
- Explore deep learning approaches for complex pattern detection.  
- Deploy as a web app for personalized obesity risk assessment.

---

## 📜 References

1. WHO. Obesity and overweight.  
2. Smith et al. (2021). Dietary patterns and obesity risk.  
3. Scikit-learn documentation.  
