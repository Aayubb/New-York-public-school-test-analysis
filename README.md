# 🏫 NYC Schools SAT Performance Analysis
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![DataCamp](https://img.shields.io/badge/DataCamp-Project-03EF62?logo=datacamp&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success) 

A data manipulation project analyzing SAT performance across New York City public schools using Python and pandas.

> This project is part of the [DataCamp Data Scientist with Python](https://www.datacamp.com/tracks/data-scientist-with-python) career track.

---

## 📋 Project Overview

This project explores SAT score data from NYC public schools to uncover insights about academic performance. It answers three key analytical questions around math excellence, overall SAT rankings, and borough-level score variability.

---

## 🔍 Analysis Tasks

### 1. Best Math Schools
Identified schools where students scored at least 80% of the maximum possible math SAT score (640 out of 800). Results are stored in a DataFrame called `best_math_schools`, containing `school_name` and `average_math`, sorted by `average_math` in descending order.

### 2. Top 10 Schools by Combined SAT Score
Ranked the top 10 schools based on the combined total of math, reading, and writing SAT scores. Results are stored in a DataFrame called `top_10_schools`, containing `school_name` and `total_SAT`, sorted by `total_SAT` in descending order.

### 3. Borough with Largest SAT Score Variability
Determined which single NYC borough has the largest standard deviation in combined SAT scores, indicating the widest spread of performance among its schools. Results are stored in a DataFrame called `largest_std_dev` with the following fields:

| Column | Description |
|---|---|
| `borough` | Name of the NYC borough |
| `num_schools` | Number of schools in the borough |
| `average_SAT` | Mean combined SAT score |
| `std_SAT` | Standard deviation of combined SAT scores |

All numeric values are rounded to two decimal places.

---

## 🛠️ Technologies Used

- **Python 3**
- **pandas** — data loading, filtering, grouping, and aggregation

---

## 📁 Repository Structure

```
├── New York School analysis.ipynb        # Main analysis notebook
├── schools.csv           # NYC schools SAT dataset
└── README.md
```
---

## 📊 Key Concepts Applied

- Boolean filtering and conditional selection
- Derived column creation and aggregation
- GroupBy operations with multiple aggregate functions
- Sorting and ranking DataFrames
- Descriptive statistics (mean, standard deviation)

## 📄 License

This project is for educational purposes as part of the DataCamp curriculum.
