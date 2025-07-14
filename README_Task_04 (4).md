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

## 📥 Dataset Source

The dataset used for this analysis was downloaded from:

**🔗 [Trump 2024 Campaign TruthSocial Truths Tweets - Kaggle](https://www.kaggle.com/datasets/muhammetakkurt/trump-2024-campaign-truthsocial-truths-tweets)**

> ⚠️ **Note:** The dataset file is not included in the GitHub repository. Please download it directly from the source if you wish to replicate the results.

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

> 🔁 Make sure to **update the file paths** in scripts to match your local machine.

---

## ⌛ Performance Summary

| Approach       | Time Taken | Notes |
|----------------|------------|-------|
| **Pure Python**| 0.09 sec   | 📚 Manual coding |
| **Polars**     | 0.12 sec   | 🚀 Fastest |
| **Pandas**     | 0.15 sec   | 🐼 Most user-friendly |

---

## 🧠 Key Insights

- All approaches produced **identical results** for shared columns.
- Pandas is ideal for ease and readability.
- Polars is optimal for large-scale, high-speed computation.
- Pure Python reinforces foundational logic but is less scalable.

---

## 💬 Reflection

This task emphasized how **different tools impact coding efficiency, speed, and scalability**. If I were mentoring a new data analyst, I’d recommend:

- **Start with Pandas** for flexibility and community support.
- **Transition to Polars** for performance scaling.
- Use **Pure Python** for learning purposes or lightweight environments.