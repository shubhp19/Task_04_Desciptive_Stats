
# 📊 Task_04_Descriptive_Stats

This repository presents descriptive statistics analysis on political social media data (e.g., Trump’s TruthSocial posts) from the 2024 U.S. Presidential campaign. The goal is to **produce identical summary statistics** using three different tools:

- ✅ Pure Python (no external libraries)
- ✅ Pandas (popular and beginner-friendly)
- ✅ Polars (blazing-fast DataFrame engine built in Rust)

---

## 📁 Contents

- `pure_python_stats.py` / `.ipynb`: Summary statistics using only Python built-ins
- `pandas_stats.py` / `.ipynb`: Pandas-powered descriptive analysis
- `polars_stats.py` / `.ipynb`: Polars-based efficient computations
- `README.md`: Instructions and insights

---

## ⚙️ How to Run

### 1. Set up Python
```bash
python -m venv venv
source venv/bin/activate  # or `venv\Scripts\activate` on Windows
```

### 2. Install dependencies
```bash
pip install pandas polars
```

### 3. Run Scripts
```bash
python pandas_stats.py
python polars_stats.py
python pure_python_stats.py
```

🔁 **Note**: Update the file paths in each script to match your system. Datasets are not included in this repository.

---

## ⏱️ Performance Summary

| Approach       | Time Taken | Notes                      |
|----------------|------------|----------------------------|
| **Pure Python**| 0.09 sec   | 🧠 Surprisingly efficient on small data |
| **Polars**     | 0.12 sec   | 🚀 Blazing fast            |
| **Pandas**     | 0.15 sec   | 🐼 User-friendly & readable|

---

## 🧠 Key Findings

- All methods yielded **consistent statistical outputs**.
- **Pure Python** outperformed here likely due to the **small dataset size**.
- **Polars** is still ideal for large-scale computation.
- **Pandas** is great for readability and rapid development.

---

## 💬 Reflection

This task reinforced how **data tool choice impacts speed and usability**:

- **Start with Pandas** for beginners or exploratory analysis.
- **Use Polars** for performance scaling and production use.
- **Pure Python** builds strong logic foundations and is dependency-free.
