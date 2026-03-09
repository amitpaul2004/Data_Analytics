
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

📷 Example Visualization
<p align="center"> 
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/Titanic_3D.png/640px-Titanic_3D.png" width="500"> 
</p>

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
