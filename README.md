# disease-prediction-system


# 🩺 Disease Prediction System

## 📌 Project Scope
- **Problem Type:** Multi-class Classification  
- **Diseases Covered:** 41  
- **Symptoms Covered:** 131  
- **Dataset Size:** 4,920 cases (perfectly balanced: 120 per disease)  

---

## 📊 Data Analysis
- **Columns:** 18 (1 disease + 17 symptom columns)  
- **Data Type:** Binary features  
- **Missing Values:** Present in last 7–17 symptom columns  

### 🔎 Key Insights
- **Most common symptoms:** fatigue, vomiting, high fever, loss of appetite, nausea  
- **Avg. symptoms per case:** 4.2 (min=1, max=17)  

---

## 🤖 Models Used
| Model | Accuracy | Notes |
|-------|----------|-------|
| Random Forest | 100% | Best performance |
| Gradient Boosting | 100% | Excellent with balanced data |
| Logistic Regression | 100% | Fast and efficient |
| SVM | 100% | Works well with high-dimensional data |

---

## 📊 Visualizations
- **Static Plots (PNG):** Disease distribution, Symptom analysis, Correlation heatmap, PCA/t-SNE plots  
- **Interactive Dashboards (HTML):** Sunburst chart, Symptom network graph, 3D scatter plot, Animated plots  

---

## 🔧 Technical Features
- **Data Processing:** Cleaning missing values, Binary encoding, 80/20 train-test split, 5-fold CV  
- **ML Techniques:** Feature importance, Hyperparameter tuning, Ensemble methods  
- **Visualization:** Matplotlib, Seaborn, Plotly, PCA, t-SNE, K-Means  

---

## 📈 Results
- **Accuracy, Precision, Recall, F1-score:** 100% (all classes)  
- **Cross-validation:** 100% ± 0%  
- **Top Features:** muscle_pain, yellowing_of_eyes, family_history, itching, fatigue  

---

## 🧪 Statistical Tests
- **Normality:** Shapiro-Wilk, D’Agostino → not normal distribution  
- **t-test:** Difference in symptom count significant  
- **Chi-square:** Strong association between symptoms & diseases  
- **ANOVA:** Significant difference between disease groups  

---

## 📁 Project Structure
