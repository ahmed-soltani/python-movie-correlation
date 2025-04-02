# 📊 Movie Correlation Analysis with Python

A data exploration and visualization project to uncover **which factors influence a movie's gross revenue** using a real-world dataset from [Kaggle](https://www.kaggle.com/datasets/danielgrijalvas/movies).

---

## 📁 Dataset

- **Source:** Kaggle – [The Movies Dataset](https://www.kaggle.com/datasets/danielgrijalvas/movies)
- **Format:** CSV
- **Columns include:** Movie title, budget, gross, rating, votes, runtime, release date, and more.

---

## 🎯 Objective

To answer the question:

> **"What features are most strongly correlated with a movie's financial success?"**

This project walks through a structured EDA (Exploratory Data Analysis) and applies statistical and visual techniques to draw insights.

---

## 🧰 Tools & Libraries

- Python 3
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 🧪 Key Analyses

- ✅ Checked for **missing data** and cleaned the dataset
- ✅ Converted columns to appropriate **data types**
- ✅ **Visualized relationships** using scatter plots and regression lines
- ✅ Explored **correlation matrix** and **heatmaps**
- ✅ Applied **log transformation** to reduce skewness in budget/gross distributions
- ✅ Calculated and sorted **ROI (Return on Investment)** per movie
- ✅ Grouped by **genre** to analyze which genres tend to earn more
- ✅ Compared original vs log-transformed visualizations side by side

---

## 📈 Sample Insights

- Movies with **higher budgets** generally tend to have **higher gross earnings** (positive correlation).
- **Votes** and **budget** show strong correlation — more expensive movies tend to get more attention.
- Some genres like **Adventure** and **Action** tend to earn higher gross on average.
- Log-transformation significantly improved visibility into trends hidden by outliers.
- A few **low-budget indie films** had massive ROI, making them hidden gems.

---

## 📂 Project Structure

