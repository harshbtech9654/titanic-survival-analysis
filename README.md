# 🚢 Titanic Survival Analytics

## 📌 Project Overview

**Titanic Survival Analytics** is an Exploratory Data Analysis (EDA) project developed as part of my **CodeAlpha Data Analytics Internship**.

The project analyzes the Titanic passenger dataset to identify patterns and relationships between **survival, gender, passenger class, ticket fare, family size, and age**.

The analysis uses Python to transform raw passenger data into structured analysis, visualizations, and meaningful insights.

---

## 🎯 Project Objectives

The project focuses on answering the following questions:

* What was the overall survival rate?
* How did survival differ by gender?
* Did passenger class influence survival probability?
* Was ticket fare associated with survival?
* How did family size affect survival?
* How did age and passenger class interact with survival?

---

## 📊 Dataset

The dataset contains **891 passenger records and 11 columns**.

### Key Variables

| Variable   | Description                                         |
| ---------- | --------------------------------------------------- |
| `Survived` | Survival status — 0 = Did not survive, 1 = Survived |
| `Pclass`   | Passenger class                                     |
| `Sex`      | Passenger gender                                    |
| `Age`      | Passenger age                                       |
| `SibSp`    | Number of siblings/spouses aboard                   |
| `Parch`    | Number of parents/children aboard                   |
| `Fare`     | Passenger ticket fare                               |
| `Embarked` | Port of embarkation                                 |

---

## 🔎 Key Analytical Insights

### 1. Overall Survival — The Reality Check

The analysis begins by comparing passengers who survived with those who did not, establishing the overall survival picture.

### 2. Gender & Survival — The "Women and Children First" Pattern

Survival outcomes are compared by gender to examine the substantial difference in survival rates and the historical evacuation pattern.

### 3. Passenger Class & Survival Probability

The project analyzes survival probability across **1st, 2nd, and 3rd class passengers** to understand the relationship between passenger class and survival.

### 4. Financial Status & Ticket Fare

Ticket fare is analyzed to investigate whether passengers paying different fare levels experienced different survival outcomes.

### 5. Family Size & Survival

A `FamilySize` feature was created using:

```python
FamilySize = SibSp + Parch + 1
```

Passengers were then grouped by family size to investigate the relationship between family structure and survival.

### 6. Passenger Class & Age Dynamics

The analysis combines **passenger class and age groups** to examine how these factors interacted with survival outcomes.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**
* **GitHub**

---

## 🔄 Analytical Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Understanding
     ↓
Data Cleaning & Validation
     ↓
Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
Data Visualization
     ↓
Insight Generation
     ↓
Final Report
```

---

## 📁 Repository Structure

```text
Titanic-Survival-Analytics/
│
├── titanic - Copy - Copy - Copy.csv
├── Titanic_Analysis.ipynb
├── Titanic_Survival_Analytics_CodeAlpha_Harsh.pdf
└── README.md
```

---

## 💡 Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data cleaning and validation
* Feature engineering
* Pandas GroupBy analysis
* Statistical comparison
* Data visualization
* Pattern identification
* Analytical storytelling
* Python-based data analysis
* Insight generation

---

## 📈 Project Outcome

This project demonstrates a complete analytical workflow from:

**Raw Data → Data Preparation → Analysis → Visualization → Insights**

The objective was not only to create visualizations, but to use data to understand the factors associated with Titanic passenger survival and communicate the findings clearly.

---

## 👨‍💻 Author

**Harsh Bhardwaj**

**B.Tech CSE | Data Analytics | Python | SQL | Excel | Power BI**

---

## 📜 Internship

This project was completed as part of the **CodeAlpha Data Analytics Internship**.

---

⭐ **Explore the repository to view the complete Python analysis and detailed project report.**
