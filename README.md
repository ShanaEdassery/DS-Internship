# 🎯 Data Science Internship Journey
> Learning Data Science from scratch — from Python basics to Machine Learning

---

## 👩‍💻 About Me
**Shana Edassery**  
Computer Science Undergraduate (2nd Year)  
Aspiring Data Scientist passionate about Data Analysis and Machine Learning.  
Currently building strong foundational skills through hands-on projects and real datasets.

---

## 📁 Projects

### 1. 📊 Employee Data Analysis (Day 1–2)
🔗 [View Project](https://github.com/ShanaEdassery/DS-Internship/blob/main/Data_analysis_EDA.ipynb)

**Goal:** Analyze employee salary and performance data  
**Dataset:** Custom dataset (5 employees)

**Key Insights:**
- Identified salary-performance mismatch in multiple employees
- Charlie: highest salary but lowest performance (overpaid)
- Diana: highest performance but not highest salary (underpaid)
- Similar salary distribution across HR and Sales departments

**Skills Used:**  
Pandas, Data Cleaning, EDA, Matplotlib, Seaborn

---

### 2. 🚢 Titanic Exploratory Data Analysis (Day 3)
🔗 [View Project](https://github.com/ShanaEdassery/DS-Internship/blob/main/titanic.ipynb)

**Goal:** Identify survival patterns in Titanic dataset  
**Dataset:** 891 passengers, 12 features

**Key Insights:**
- Female survival rate (~74%) significantly higher than male (~19%)
- First-class survival (~63%) much higher than third class (~24%)
- Children (age 0–10) had higher survival rates
- Positive relationship between fare and survival probability
- Analysis supports "women and children first" pattern

**Skills Used:**  
Pandas, Data Cleaning, EDA, Matplotlib, Seaborn

---

### 3. 📈 Statistical Analysis on Titanic (Day 4–5)
🔗 [View Project](https://github.com/ShanaEdassery/DS-Internship/blob/main/day4_statistics_Titanic.ipynb)

**Goal:** Validate findings using statistical methods  
**Dataset:** Titanic dataset (891 passengers)

**Key Insights:**
- Mean age ≈ 29.36 with slight right skew
- Detected 116 outliers in Fare using IQR method (max ≈ 512)
- Fare shows moderate correlation with survival (~0.26)
- Performed independent t-test on gender vs survival
- Found statistically significant difference (p < 0.05)
- 95% confidence interval for female survival: 69% – 79%

**Skills Used:**  
Pandas, NumPy, SciPy, Statistics, Hypothesis Testing

---

### 4. 🤖 Titanic Survival Prediction — ML Study (Day 6)
🔗 [View Project](https://github.com/ShanaEdassery/DS-Internship/blob/main/ml_prediction_titanic.ipynb)

**Goal:** Build and compare ML classification models  
**Dataset:** 891 Titanic passengers, 6 features  
**Type:** Supervised Learning — Binary Classification

**Model Comparison:**

| Model | Configuration | Accuracy |
|-------|--------------|---------|
| Logistic Regression | max_iter=1000 | **81.01%** ✅ Winner |
| Decision Tree | max_depth=3 | 79.89% |
| Decision Tree | max_depth=5 | 80.45% |
| Decision Tree | max_depth=10 | 78.21% ❌ Overfit |

**Key Findings:**
- Logistic Regression outperformed all Decision Tree variants
- Overfitting detected at Decision Tree depth 10
- Simpler models can outperform complex ones
- Gender and class were strongest survival predictors
- Decision Tree visualization confirmed EDA findings

**Skills Used:**  
Scikit-learn, Logistic Regression, Decision Tree,
Model Evaluation, Confusion Matrix, Overfitting Detection,
Hyperparameter Tuning, Model Comparison

---

## 🛠️ Skills

### Programming
- Python
- Pandas
- NumPy
- SciPy

### Data Analysis
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Hypothesis Testing
- Confidence Intervals
- Outlier Detection (IQR)
- Correlation Analysis

### Machine Learning
- Supervised Learning (Binary Classification)
- Logistic Regression
- Decision Tree Classifier
- Hyperparameter Tuning (max_depth)
- Train/Test Split (80/20)
- Model Evaluation & Comparison
- Confusion Matrix Analysis
- Overfitting Detection & Prevention
- Scikit-learn

### Visualization
- Matplotlib
- Seaborn
- Bar Plots, Histograms, Box Plots, Heatmaps

---

## ⚙️ Tools
- Jupyter Notebook
- GitHub
- Scikit-learn

---

## 📚 Next Steps
- End-to-End Data Science Project
- SQL for Data Analysis
- Advanced ML Algorithms
- Deep Learning Fundamentals

---

## 🎯 Goal
Become a Data Scientist and contribute to impactful real-world projects

---

*This repository is updated regularly as I learn and grow 🌱*
