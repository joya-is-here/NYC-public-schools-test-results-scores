# 🏫 NYC Public Schools SAT Analysis

Every year, American high school students take the SAT — a standardized test designed to evaluate literacy, numeracy, and writing skills. The SAT consists of three sections:

- 📘 **Reading**  
- 📐 **Math**  
- ✍️ **Writing**

Each section is scored out of a **maximum of 800 points**, and the results play a crucial role in college admissions decisions across the country.

## 🎯 Project Objective

This project focuses on analyzing SAT performance data from New York City (NYC) public high schools using Python and pandas.

The dataset provided, `schools.csv`, contains SAT score information for schools across all five boroughs of NYC.

---

## 🧩 Key Questions Answered

### 1. 🧮 Which NYC schools have the best math results?

- We identify schools with **math scores ≥ 640**, which is 80% of the maximum possible score.
- These are stored in a DataFrame called `best_math_schools`, sorted by `average_math` in descending order.

### 2. 🏆 What are the top 10 performing schools based on combined SAT scores?

- We calculate a new column `total_SAT` as the sum of average math, reading, and writing scores.
- The top 10 schools are stored in a DataFrame named `top_10_schools`, sorted by `total_SAT`.

### 3. 🗺️ Which borough has the highest standard deviation in combined SAT scores?

- We group the data by borough and compute statistics:
  - Total number of schools
  - Mean `total_SAT`
  - Standard deviation of `total_SAT`
- The result is stored in a DataFrame called `largest_std_dev`.

All numeric values are rounded to two decimal places for clarity.

---

## 📦 Tools & Libraries Used

- Python 3
- pandas
- matplotlib

---

## 📊 Visualization

Simple bar charts and error bar plots are included to clearly represent school performance and SAT score variation across boroughs.

---

## 📁 Dataset

- File: `schools.csv`
- Columns include: `school_name`, `average_math`, `average_reading`, `average_writing`, and `borough`

---

> This beginner-level project is part of a learning journey toward becoming a top-tier data analyst.

