# edX Courses Dataset - Data Analysis

This project analyzes an edX courses dataset containing information about online courses such as titles, enrollment numbers, subjects, prices, levels, and institutions.

# 📁 Dataset Overview

- **Rows**: 975 courses
- **Columns**: 16 (including `title`, `subject`, `price`, `institution`, `Level`, etc.)

### Key Fields
- `title`: Course name
- `subject`: Topic of the course (e.g., Data Analysis, Computer Science)
- `institution`: University or provider (e.g., Harvard, MIT)
- `n_enrolled`: Number of enrolled students (cleaned to numeric)
- `price`: Textual price info (e.g., FREE or '$49')
- `price_clean`: Extracted numeric price value
- `Level`: Introductory, Intermediate, Advanced

---

## 🧹 Data Cleaning

- Removed commas from `n_enrolled` and converted to number.
- Extracted dollar values from `price` using regex.
- Created int form string for numeric analysis.

---

# 📊 Analysis Performed

1. **Top 10 Most Enrolled Courses**
2. **Course Distribution by Subject**
3. **Top 10 Institutions by Course Count**
4. **Average Price by Subject**
5. **Course Count by Difficulty Level**

---

# 📈 Visualizations

- Bar charts using Matplotlib + Seaborn
- Clean titles, labels, and formatting for easy interpretation

---

## 🔧 Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn
