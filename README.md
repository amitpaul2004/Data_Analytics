# 🚀 Data Science ( Analytics) & Machine Learning 

<p align="center">

<img src="https://readme-typing-svg.herokuapp.com/?lines=Data+Analytics+Projects;Machine+Learning+Portfolio;Visualization+Beyond+Basics;Python+%7C+Pandas+%7C+Seaborn;Real+World+Datasets+Analysis&center=true&width=500&height=45">

</p>

---

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn)

</p>

---

# 📊 Project Overview

This repository is a **comprehensive collection of Data Science and Machine Learning projects**.

It demonstrates:

✨ Data Analysis  
🤖 Machine Learning  
📊 Statistical Testing (ANOVA)  
📈 Advanced Visualization  
🎬 Animated Graphs  
🌍 Real-world datasets  

---

# 📁 Repository Structure 

📦 Project Root 
- 📂 codes → Jupyter notebooks (ML, EDA, visualization)
- 📂 data → Real-world datasets (CSV, Excel)
- 📜 README.md

---

---

# 🔥 Featured Projects

## 🚢 Titanic Survival Analysis
✔ ANOVA testing  
✔ Survival prediction  
✔ Confusion matrix + ROC curve  
✔ Advanced visualization  

---

## 📱 Social Media Analytics
✔ Engagement analysis  
✔ Trend detection  
✔ Histogram & pie charts  

---

## 🏏 IPL Data Analysis
✔ Player performance  
✔ Career graph  
✔ Team prediction model  

---

## 🎬 Netflix Series Analysis
✔ Monthly trending  
✔ Genre popularity  
✔ Viewer insights  

---

## 🌍 Earthquake Analysis
✔ Magnitude distribution  
✔ Time trend analysis  
✔ Geographic insights  

---

## 📈 Economic Growth Prediction
✔ Future trend modeling  
✔ Dataset generation  
✔ Visualization forecasting  

---

## 🤖 Machine Learning Models
✔ Logistic Regression  
✔ Linear Regression  
✔ Classification & Prediction  
✔ Model evaluation  

---

## 🎨 Visualization Beyond Basics

- Pairplots  
- Heatmaps  
- Violin plots  
- KDE plots  
- 3D Visualizations  
- Animated graphs  

---

Dataset loaded using:

```python
import seaborn as sns
df = sns.load_dataset("titanic")
```

---

## 📈 Analysis Performed

### 1️⃣ Data Cleaning
- Removed missing values
- Selected relevant columns
- Prepared dataset for statistical testing  

### 2️⃣ Data Visualization
The project includes multiple visualizations:

- 📊 Bar plots
- 📉 Histograms
- 📦 Boxplots
- 🎬 Animated survival visualization

Example:
```python
sns.barplot(x="class", y="survived", hue="sex", data=df)
```
3️⃣ Statistical Analysis (Two-Way ANOVA)
This analysis tests:

- Effect of Gender
- Effect of Passenger Class
- Interaction between Gender × Class

Example model:
```python
from statsmodels.formula.api import ols

model = ols('survived ~ C(sex) * C(Q("class"))', data=df).fit()
```

---
🎬 Animated Visualization

This project also includes animated plots using Matplotlib.
```python
import matplotlib.animation as animation
```
Animated plots dynamically display survival rates across classes.

---

# ⚙️ Tech Stack

```bash
Python | Pandas | NumPy | Seaborn | Matplotlib | Plotly | Scikit-learn
```
## ⚙️ Technologies Used

- Python  
- Pandas  
- Seaborn  
- Matplotlib  
- Statsmodels  
- Jupyter Notebook

---

📷 File Structure

```tree
├── 📁 .ipynb_checkpoints
│   ├── 📄 accident_predict-checkpoint.ipynb
│   ├── 📄 gender-checkpoint.ipynb
│   ├── 📄 ios_android-checkpoint.ipynb
│   ├── 📄 kolkata-checkpoint.ipynb
│   ├── 📄 mock_test-checkpoint.ipynb
│   ├── 📄 testing-checkpoint.ipynb
│   └── 📄 train-checkpoint.ipynb
├── 📁 codes
│   ├── 📁 .ipynb_checkpoints
│   │   ├── 📄 advanced.ipynb
│   │   ├── 📄 climate.ipynb
│   │   ├── 📄 earth_quake.ipynb
│   │   ├── 📄 phone-pay_razar_paypal-checkpoint.ipynb
│   │   ├── 📄 test-checkpoint.ipynb
│   │   ├── 📄 titanic-checkpoint.ipynb
│   │   ├── 📄 train-checkpoint.ipynb
│   │   └── 📄 visual.ipynb
│   ├── 📄 JIS.ipynb
│   ├── 📄 accident_predict.ipynb
│   ├── 📄 adavance_pd.ipynb
│   ├── 📄 assigment1.ipynb
│   ├── 📄 breast_cancer.ipynb
│   ├── 📄 earth_quake_2.ipynb
│   ├── 📄 ecomic_gwrth.ipynb
│   ├── 📄 finalproject.ipynb
│   ├── 📄 gender.ipynb
│   ├── 📄 ios_android.ipynb
│   ├── 📄 ipl.ipynb
│   ├── 📄 jis_university.db
│   ├── 📄 jis_university_students.xlsx
│   ├── 📄 kolkata.ipynb
│   ├── 📄 match.ipynb
│   ├── 📄 mock_test.ipynb
│   ├── 📄 netflix.ipynb
│   ├── 📄 new_titanic.ipynb
│   ├── 📄 personl_data.ipynb
│   ├── 📄 phone-pay_razar_paypal.ipynb
│   ├── 📄 socia1l.ipynb
│   ├── 📄 social.ipynb
│   ├── 📄 social_media_usage.xlsx
│   ├── 📄 social_use.ipynb
│   ├── 📄 student_fruit.ipynb
│   ├── 📄 testing.ipynb
│   ├── 📄 testing3.ipynb
│   ├── 📄 titanic.ipynb
│   ├── 📄 titanic2.ipynb
│   ├── 📄 titanic3.ipynb
│   ├── 📄 titanic4ANOVA.ipynb
│   └── 📄 train.ipynb
├── 📁 data
│   ├──  ( all data of .ipynb files )
└── 📝 README.md
```

---

🚀 How to Run the Project

Clone the repository:
```git
git clone https://github.com/yourusername/titanic-analysis.git
 ```
Install required libraries
```git 
pip install pandas seaborn matplotlib statsmodels
```
Run Jupyter Notebook
```git 
jupyter notebook
```
--- 

👨‍💻 Author

Amit Paul

💻 Data Science | Python | Machine Learning

---

⭐ Support

If you like this project:

- ⭐ Star the repository
- 🍴 Fork the project
- 🚀 Share it with others


