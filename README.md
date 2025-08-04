# Task 1: Data Cleaning and Preprocessing

## 📊 Dataset
**Netflix Movies and TV Shows**  
- Source: [Kaggle - Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Records: 8,807
- Columns: 12  
- Description: Contains data about TV shows and movies available on Netflix including title, cast, director, country, date added, release year, rating, and more.

---

## 🛠 Tools Used
- Python 3.12.7
- Pandas
- VS Code

---

## 🧹 Cleaning Steps Performed

### ✅ General:
- Loaded the dataset using Pandas
- Inspected data types, missing values, and duplicate records

### ✅ Column Renaming:
- Renamed `exshow_id` → `show_id`
- Cleaned all column names to be lowercase with underscores

### ✅ Missing Value Handling:
- Filled missing values in:
  - `director` → `"Unknown"`
  - `cast` → `"Unknown"`
  - `duration` → `"Unknown"`
- Dropped rows with missing values in:
  - `country`
  - `rating`
  - `date_added`

### ✅ Data Formatting:
- Converted `date_added` to proper datetime format
- Standardized text fields:
  - `type` → lowercase
  - `rating` → uppercase
  - Trimmed spaces in `country` and `listed_in`

### ✅ Duplicate Handling:
- Removed all duplicate rows

---

## 🧾 Output
- Cleaned Dataset: `cleaned_dataset.csv`
- Total rows after cleaning: (your final row count here, e.g., 8,654)

---

## 💡 Key Learnings
- Practical experience with Pandas for data cleaning
- Handling nulls, duplicates, text standardization, and datetime conversion
- Importance of preprocessing for reliable analysis

---

