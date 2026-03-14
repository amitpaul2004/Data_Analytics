<p align="center">

<img src="https://readme-typing-svg.herokuapp.com/?lines=Titanic+Data+Analysis;ANOVA+Statistical+Testing;Python+Data+Science+Project;Data+Visualization+with+Seaborn;Machine+Learning+Ready+Dataset&center=true&width=500&height=45">

</p>

# 🚢 Titanic Survival Analysis

---

## 📊 Project Overview

This project analyzes the **Titanic passenger dataset** to identify patterns that influenced survival rates.

The project demonstrates:

- 📊 Data analysis
- 📈 Data visualization
- 🎬 Animated plots
- 📉 Statistical testing using **ANOVA**

---

## 📁 Dataset

Dataset used: **Titanic Dataset (Seaborn)**

| Column | Description |
|------|------|
| survived | Survival status (0 = No, 1 = Yes) |
| sex | Passenger gender |
| class | Passenger class |
| age | Passenger age |
| fare | Ticket price |

Dataset loaded using:

```python
import seaborn as sns
df = sns.load_dataset("titanic")
```

## ⚙️ Technologies Used

- Python  
- Pandas  
- Seaborn  
- Matplotlib  
- Statsmodels  
- Jupyter Notebook

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
📊 Key Insights

-📌 Female passengers had higher survival rates
-📌 First-class passengers survived more often
-📌 Gender and passenger class significantly influence survival probability

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
│   ├── 📄 Road_Accidents_2017-Tables_3.7.csv
│   ├── 📄 antutu_android_vs_ios_v3.csv
│   ├── 📄 earthquake_1995-2023.csv
│   ├── 📄 india_economic_growth_large_dataset.csv
│   ├── 📄 indian_cricket_team_t20.csv
│   ├── 📄 ipl_players_career_dataset.xlsx
│   ├── 📄 kolkata-2025-domestic.csv
│   ├── 📄 kolkata-2025-international.csv
│   ├── 📄 netflix_series_monthly_popularity_dataset (1).xlsx
│   ├── 📄 paypal_transactions_dataset.xlsx
│   ├── 📄 phonepe_transactions_dataset.xlsx
│   ├── 📄 query.csv
│   ├── 📄 razer_dataset_2026.xlsx
│   ├── 📄 social_media_engagement_dataset.csv
│   ├── 📄 social_media_trends_dataset.xlsx
│   ├── 📄 student_fruit_dataset.xlsx
│   ├── 📄 vgsales.csv
│   └── 📄 youtube_trending_videos_dataset_2026.xlsx
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


---

### If you want, I can also show you how to add:

- **GitHub contribution graph animation**
- **3D snake animation**
- **profile stats cards**
- **project demo GIF**

These make GitHub repos look **extremely impressive.**
