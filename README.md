# 📊 Exploratory Data Analysis (EDA) – gender_submission.csv  
### Data Analyst Internship – Task 5  
### Author: YOUR NAME

---

## 📘 Project Overview
This project contains the Exploratory Data Analysis (EDA) for the dataset **gender_submission.csv**, which is part of the Kaggle Titanic Competition.  
This file is typically used as a *sample submission file* and contains predicted survival outcomes for passengers.

Due to its limited structure (only two columns), the goal of this task is to demonstrate EDA techniques, plotting, insights, and documentation.

---

## 📂 Dataset Details

**Dataset:** `gender_submission.csv`  
**Total Rows:** 418  
**Total Columns:** 2  

### Columns Included:
| Column Name | Description |
|-------------|-------------|
| **PassengerId** | Unique identifier of each passenger |
| **Survived** | Predicted survival status (0 = Not Survived, 1 = Survived) |

This dataset does **not** contain features such as Age, Sex, Pclass, Fare, or Cabin.  
Therefore, analysis is limited but performed as required for Task 5.

---

## 🧪 Objectives of the Task
- Load dataset using Pandas  
- Check structure and basic statistics  
- Visualize distribution of Survived values  
- Perform basic correlation analysis  
- Generate graphs using Matplotlib & Seaborn  
- Summarize insights in a clean PDF report  
- Export cleaned dataset  

---

## ⚙️ Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📁 Files Included in This Submission

| File | Description |
|------|-------------|
| **Task5_EDA.ipynb** | Complete Jupyter Notebook with all EDA code |
| **gender_submission.csv** | Dataset used for analysis |
| **clean_gender_submission.csv** | Clean dataset exported from notebook |
| **EDA_Report.pdf** | Final report containing findings |
| **README.md** | Project documentation |

---

## 📈 Key Insights
- Dataset is very limited: only PassengerId & Survived columns.
- No missing values were found in the dataset.
- Survival predictions distribution:
  - **0 = 266 passengers (Not Survived)**
  - **1 = 152 passengers (Survived)**  
- Correlation analysis shows no meaningful relationship due to lack of features.
- The dataset is meant **only for sample submission**, not for full analysis.
- A complete Titanic analysis requires `train.csv` with features like Age, Sex, Fare, etc.

---

## 📊 Visualizations Created
- Survived Count Plot  
- PassengerId Histogram  
- Correlation Heatmap  
- Dataset Pairplot  

---

## 📄 Summary Conclusion
The `gender_submission.csv` dataset is clean but extremely limited.  
It should primarily be used as a **submission template** for the Titanic Kaggle competition.

To perform full EDA, classification, or modeling, the original **train.csv** dataset is required because it contains actual passenger features.

---

## 🚀 How to Run the Notebook
1. Place `gender_submission.csv` in your working directory.  
2. Open the file **Task5_EDA.ipynb** in Jupyter Notebook.  
3. Run each cell in order.  
4. A cleaned version of the dataset will be saved automatically.

---

## 👤 Author
NARKHEDE OM RAHUL  
Data Analyst Intern  
(8cnarkhedeom33@gmail.com)

---

## ✔️ End of README
