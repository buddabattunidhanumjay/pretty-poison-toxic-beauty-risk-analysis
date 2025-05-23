# Pretty Poison: Health Risks of Toxic Beauty

This capstone project investigates the health risks associated with exposure to cosmetic chemicals such as parabens, phthalates, and triclosan. Using data from NHANES (2009–2012), the study explores potential links between these exposures and breast cancer incidence, applying data preprocessing, statistical analysis, feature engineering, and machine learning to generate public health insights.

## 🎯 Project Objective

To assess whether harmful chemicals found in everyday personal care products are linked to breast cancer risk, using nationally representative health survey data.

---

## 📂 Project Files

### 📁 Data Files (NHANES Raw .xpt Format)
- `2009-2010-Demographics.xpt`
- `2009-2010-Medical-Conditions.xpt`
- `2009-2010-Parabens.xpt`
- `2009-2010-Phthalates.xpt`
- `2011-2012-Demographics.xpt`
- `2011-2012-Medical-Conditions.xpt`
- `2011-2012-Parabens.xpt`
- `2011-2012-Phthalates.xpt`

### 🧪 Processed Data
- `2009-2012-Filtered-Data.xlsx`: Cleaned and feature-engineered dataset

### 📓 Notebook
- `2009-2012.ipynb`: Jupyter notebook for data loading, cleaning, EDA, modeling, and evaluation

### 📑 Final Outputs
- `Final_Project_Report_Dhanumjay_Buddabattuni.pdf`
- `Dhanumjay_Buddabattuni.pptx`: Slide deck summarizing findings and future directions

---

## 🛠 Tools & Technologies

- **Languages**: Python (Pandas, NumPy, Scikit-learn, XGBoost)
- **Visualization**: Seaborn, Matplotlib
- **Statistical Analysis**: T-tests, Odds Ratio Analysis
- **Machine Learning Models**: Logistic Regression, Random Forest, XGBoost

---

## 📊 Key Contributions

- Cleaned and merged raw NHANES datasets
- Engineered features such as `MPB_per_Age`, `Triclosan x Age`, `Total Phthalates`
- Performed statistical significance testing (T-tests)
- Built ML models with strong performance (XGBoost achieved perfect recall)
- Identified Triclosan and Age as strongest predictors of breast cancer risk
- Delivered insights through a structured report and professional presentation

---

## 🚀 Results Summary

- **Best Model**: XGBoost (perfect recall, high precision)
- **Significant Predictors**: Triclosan, MEP, MPB, Age
- **Implications**: Findings support regulatory concerns about endocrine-disrupting chemicals in personal care products

---

## 🔮 Future Scope

- Apply SHAP/LIME for model explainability  
- Perform longitudinal analysis on repeated exposures  
- Validate results on other populations or NHANES years  
- Contribute to public health awareness and cosmetic safety advocacy

---

## 📬 Contact

**Dhanumjay Buddabattuni**  
📧 buddabattunidhanumjay@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/dhanumjaybuddabattuni) | [GitHub](https://github.com/buddabattunidhanumjay)
