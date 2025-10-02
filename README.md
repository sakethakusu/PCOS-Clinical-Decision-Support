# PCOS-Clinical-Decision-Support
Data-driven Clinical Decision Support system for Polycystic Ovary Syndrome (PCOS) using logistic regression and Random Forest. Predicts cardiovascular/metabolic risks from clinical datasets, enabling early intervention and personalized care. Includes data, preprocessing, model code, and presentation.
# 💡 PCOS Clinical Decision Support (CDS) System  

A **data-driven Clinical Decision Support system** designed to predict cardiovascular and metabolic risks in women with **Polycystic Ovary Syndrome (PCOS)**.  
The project applies **logistic regression and Random Forest models** to clinical datasets to support early intervention and personalized patient care.  

---

## 📌 Project Overview  
Polycystic Ovary Syndrome (PCOS) affects **1 in 10 women worldwide**, increasing risks of **cardiovascular disease, diabetes, and infertility**.  
This project builds predictive models to:  

✔️ Identify key risk factors (BMI, insulin resistance, cIMT, arterial stiffness)  
✔️ Enhance early diagnosis and prevention strategies  
✔️ Provide clinicians with actionable insights through data-driven analysis  

---

## 🚀 Methodology  

1. **Data Collection** – Retrospective & prospective studies (sample sizes: 80–174,000)  
2. **Data Preprocessing** – Cleaning missing values, encoding categorical variables, normalization  
3. **Feature Selection** – Clinical predictors such as BMI, age, insulin resistance, arterial stiffness  
4. **Model Training** – Logistic Regression (max_iter=1000), Random Forest (n_estimators=100)  
5. **Evaluation** – Accuracy, precision, recall, confusion matrix  

---

## 📊 Key Findings  
- **Logistic Regression Accuracy**: 91.6%  
- **Random Forest Accuracy**: 25% (limited dataset size & imbalance)  
- **Top Predictors**: BMI, cIMT (Carotid Intima-Media Thickness), Age, Insulin resistance  
- **Insight**: Clinical features strongly predict cardiovascular risks in PCOS patients  

---

## 📊 Results  
- **Logistic Regression Accuracy:** 91.6%  
- **Random Forest Accuracy:** 25%  
- **Key Predictors:** Mean Age, cIMT, PCOS n, Control n  
- **Outputs:** Confusion Matrix, Correlation Heatmap, Feature Importance Plots  

---

## ⚡ Challenges  
- Limited **genetic and lifestyle data** in available studies  
- **Sample diversity** limits generalizability  
- Logistic regression assumptions simplify complex PCOS interactions  

---

## 🔮 Future Directions  
- Expand dataset with **genetic + lifestyle features**  
- Explore **advanced ML models (XGBoost, Neural Nets)**  
- Add **AUC-ROC analysis** for better model discrimination  
- Deploy as a **clinical tool** integrated with **EHR systems**  

---

## 📦 Installation  

```bash
# Clone the repository
git clone https://github.com/yourusername/PCOS-Clinical-Decision-Support.git
cd PCOS-Clinical-Decision-Support

# Install dependencies
pip install -r requirements.txt
