# Titanic-Dataset---Exploratory-Data-Analysis-EDA

## 📘 Project Overview
This project explores the **Titanic dataset** to identify key factors that influenced passenger survival.  
The dataset contains demographic, social, and economic information about passengers aboard the Titanic.  
The goal is to perform **data cleaning, visualization, and statistical analysis** to uncover insights and patterns.

---
## 🧰 Tools and Libraries Used
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📊 Data Analysis Steps

### 1️⃣ Data Inspection
- Used `.info()` to check data types and missing values.  
- Used `.describe()` for summary statistics.  
- Used `.value_counts()` to analyze categorical features.

### 2️⃣ Data Cleaning
- Handled missing values in `Age`, `Embarked`, and `Cabin`.  
- Created a new column `Cabin_Deck` by extracting the first letter of the cabin.

### 3️⃣ Visualization and Insights
- **Pairplot (`sns.pairplot`)** → Analyzed relationships between `Age`, `Fare`, `SibSp`, `Parch`, and `Survived`.  
- **Heatmap (`sns.heatmap`)** → Checked correlations between numerical variables.  
- **Histograms** → Showed distribution of `Age` and `Fare`.  
- **Boxplots** → Compared `Fare` across passenger classes.  
- **Scatterplots** → Visualized `Age` vs. `Fare` colored by survival.

---

## 📈 Key Findings
| Feature | Observation |
|----------|--------------|
| Gender | Females had a much higher survival rate |
| Class | 1st class passengers had better survival chances |
| Fare | Higher fares were linked to higher survival probability |
| Age | Younger passengers slightly more likely to survive |
| Cabin | 77% missing data, but upper decks showed better survival |
| Embarked | Most passengers boarded from Southampton |

---

## 💡 Conclusion
- **Socioeconomic status, gender, and class** had a significant effect on survival.  
- Data visualization helped identify meaningful trends.  
- The dataset demonstrates how exploratory data analysis can uncover insights before building predictive models.

# Open Jupyter Notebook
task-5 EDA Titanic data.ipynb
