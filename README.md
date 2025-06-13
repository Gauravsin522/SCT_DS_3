

# 📊 SkillCraft Internship – Task 3

## 📁 Project Title

**Bank Marketing Campaign Analysis using Decision Tree Classifier**

---

## 🧩 Objective

To analyze and model client data from a Portuguese banking institution to predict whether a customer will subscribe to a term deposit (`y`), using exploratory data analysis and a Decision Tree Classifier.

---

## 📌 Dataset Overview

* **Source**: Bank Marketing Dataset (UCI Repository)
* **Records**: Each row represents a marketing campaign call
* **Target Variable**: `y` (yes/no – whether the client subscribed)

### 🔑 Key Features:

* Demographic: `age`, `job`, `marital`, `education`
* Financial: `balance`, `loan`, `housing`
* Campaign-related: `contact`, `day`, `month`, `duration`, `campaign`, `pdays`, `previous`, `poutcome`

---

## 🔍 Project Workflow

1. **Data Ingestion**

   * Properly handled semicolon-separated file using pandas.
2. **Data Cleaning**

   * Converted categorical labels
   * Checked and handled class imbalance and nulls
3. **EDA**

   * Univariate and bivariate visualizations
   * Insightful relationships between features and target
4. **Feature Engineering**

   * One-hot encoding for categorical variables
5. **Model Building**

   * Trained a Decision Tree Classifier
   * Evaluated using accuracy, precision, recall, F1-score
6. **Interpretability**

   * Visualized a limited-depth version of the tree

---

## 📈 Model Performance

* Evaluation metrics calculated on test set
* Model performance discussed in the final notebook section

---

## ✅ Outcome

* Built a complete EDA + ML pipeline
* Derived actionable insights from the data
* Demonstrated explainability through a tree-based model

---

## 🧑‍💻 Contributor

**Gaurav Singh**
*Data Science Intern – SkillCraft Technology*
📅 Task Completed: June 13, 2025

