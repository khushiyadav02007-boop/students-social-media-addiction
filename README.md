# students-social-media-addiction
# Students Social Media Addiction Analysis

A complete end-to-end data science project that analyzes social media usage patterns 
among students and predicts addiction levels using Machine Learning.

---

##  Project Overview

Social media has become a major part of students' daily lives. While it helps with 
communication and learning, excessive use can negatively affect:

-  Mental Health
- Sleep Quality
-  Academic Performance
-  Personal Relationships

This project analyzes students' social media usage patterns and builds ML models 
to predict addiction scores and identify the most influential factors.

---

##  Project Pipeline

1. **Import Libraries** — Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
2. **Load Dataset** — Loaded and explored using Pandas
3. **Data Exploration** — Checked shape, column names, data types, missing values
4. **Data Cleaning** — Handled missing values and inconsistencies
5. **Outlier Detection** — Detected and removed outliers using the IQR method
6. **EDA (Exploratory Data Analysis)**
   - Histograms
   - Boxplots
   - Countplots
   - Correlation Heatmap
7. **Feature Engineering** — Created new features:
   - `Usage_Sleep_Ratio`
   - `Mental_Conflict_Score`
8. **Label Encoding** — Converted categorical columns to numerical format
9. **Train-Test Split** — Divided dataset into training and testing sets
10. **Feature Scaling** — Applied StandardScaler
11. **Model Training** — Trained two ML models
12. **Evaluation** — Compared models using MAE, MSE, RMSE, R² Score
13. **Visualization** — Actual vs Predicted, Feature Importance, Model Comparison

---

##  Models Used

| Model | Description |
|-------|-------------|
| Linear Regression | Baseline model for predicting addiction scores |
| Random Forest Regressor | Best performing model ✅ |

**Random Forest outperformed Linear Regression** with higher R² score and lower prediction error.

---

##  Key Findings

- **Mental Health Score** and **Conflicts Over Social Media** are the most important 
  features affecting addiction score prediction
- Students spending more hours on social media showed higher stress, anxiety, and 
  reduced academic performance
- The correlation heatmap confirmed strong relationships between mental health, 
  conflicts, and addiction levels

---

##  Dataset Features Studied

| Feature | Description |
|---------|-------------|
| Daily Usage Hours | Hours spent on social media per day |
| Sleep Duration | Hours of sleep per night |
| Mental Health Score | Score indicating mental well-being |
| Academic Impact | Effect of social media on studies |
| Social Conflicts | Conflicts arising due to social media use |

---

##  Tools & Libraries

- **Language:** Python
- **Data Handling:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Models:** Linear Regression, Random Forest Regressor
- **Preprocessing:** StandardScaler, Label Encoding, IQR Outlier Removal

---

##  Skills Demonstrated

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Model Building
- Model Evaluation & Comparison
- Data Visualization

---

##  Author

**Khushi**  
Feel free to connect and give feedback!
