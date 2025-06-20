# 🎥 Movie Data Cleaning Project.

This project demonstrates how to clean a raw movie dataset using **Python**, **Pandas**, and **Jupyter Notebook**.

---

## 📁 Files Included

| File Name             | Description                                      |
|-----------------------|--------------------------------------------------|
| `Pandas2F.ipynb`      | Notebook with step-by-step data cleaning         |
| `movies_cleaned.csv`  | Final cleaned dataset ready for analysis         |

---

## 🧹 Cleaning Summary

The original dataset (`movies.csv`) contained:
- Newlines and unnecessary spaces in text
- Year values with parentheses like `(2021)`
- `VOTES` column stored as strings with commas
- Missing values in `RATING` and `RunTime`
- A nearly empty `Gross` column

### ✔️ Cleaning Steps Performed:
- Stripped extra whitespace and newlines
- Extracted 4-digit years using regular expressions
- Converted `VOTES` from strings to numeric values
- Dropped `Gross` due to missing data
- Removed rows with missing `RATING` or `RunTime`

---

## 🔧 Tools Used

- [Python 3](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [GitHub](https://github.com/)

---

## 🚀 How to Run This Project

1. Clone or download the repository  
   ```bash
   git clone https://github.com/Thanusan04/-movie-data-cleaning.git
