# 📊 Task_04_Descriptive_Stats

This repository contains descriptive statistics analysis on political social media data from the 2024 U.S. Presidential campaign. The goal of this task is to **replicate identical summary results** using three distinct approaches:

- ✅ Pure Python (no external libraries)
- ✅ Pandas (popular DataFrame library)
- ✅ Polars (high-performance, Rust-based DataFrame library)

---

## 📁 Contents

- `pure_python_stats.py` / `.ipynb`: Descriptive stats using only built-in Python
- `pandas_stats.py` / `.ipynb`: Analysis using Pandas
- `polars_stats.py` / `.ipynb`: Analysis using Polars
- `README.md`: This file

---

## ⚙️ How to Run

### 1. Set up Python
```bash
python3 -m venv venv
source venv/bin/activate  # or `venv\Scripts\activate` on Windows
```

### 2. Install dependencies
```bash
pip install pandas polars
```

### 3. Run any file
```bash
python pandas_stats.py
# OR
python polars_stats.py
# OR
python pure_python_stats.py
```

> 🔁 Make sure to **update the file paths** in scripts to match your local machine. Dataset files are not included in this repo.

---

## ⌛ Performance Summary

| Approach       | Time Taken | Notes |
|----------------|------------|-------|
| **Polars**     | 8.84 sec   | 🚀 Fastest |
| **Pure Python**| 17.00 sec  | 📚 Manual coding |
| **Pandas**     | 23.00 sec  | 🐼 Most user-friendly |

---

## 🧠 Key Insights

- All approaches produced **identical results** for shared columns across Facebook Ads, Facebook Posts, and Twitter Posts datasets.
- Pandas is ideal for ease and readability.
- Polars is optimal for large-scale, high-speed computation.
- Pure Python reinforces foundational logic but is less scalable.

---

## 💬 Reflection

This task emphasized how **different tools impact coding efficiency, speed, and scalability**. If I were mentoring a new data analyst, I’d recommend:

- **Start with Pandas** for flexibility and community support.
- **Transition to Polars** for performance scaling.
- Use **Pure Python** only for learning or constraints with dependencies.