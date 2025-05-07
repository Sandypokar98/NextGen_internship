# NextGen_internship
# 🧠 Data Science Internship – Week 1 Report

## 👤 Name: Sandeep Ravaji Patel

**Domain:** Data Science
**Week:** 1

---

## 📌 Task Description

### 🌟 Objective:

To begin Python programming and build a strong foundation through core syntax, control structures, data types, functions, and data manipulation.

### ✅ Tasks Completed:

* **Python Basics**

  * Explored Python data types: `int`, `float`, `str`, `list`, `dict`
  * Applied conditional logic using `if`, `elif`, and `else`
  * Used loops (`for`, `while`) for iteration
  * Defined and used functions for modular programming

* **Data Manipulation with Lists and Dictionaries**

  * Used `lists` and `dictionaries` to store, access, and process structured data
  * Implemented basic problems such as:

    * Counting word frequency
    * Grouping data by category (e.g., employee departments)
    * Filtering data (e.g., students passing all subjects)

* **Jupyter Notebook Practice**

  * **Notebook 1:** Implemented logic for palindromes, Armstrong numbers, power calculation, and digit analysis
  * **Notebook 2:** Created small applications like a contact book, student marks analyzer, and inventory manager

---

## 💻 Code Snippets (Examples)

```python
# Palindrome Checker
def is_palindrome(n):
    return str(n) == str(n)[::-1]
```

```python
# Group Employees by Department
employees = [{'name': 'John', 'dept': 'HR'}, {'name': 'Eve', 'dept': 'IT'}]
dept_dict = {}
for emp in employees:
    dept_dict.setdefault(emp['dept'], []).append(emp['name'])
```

```python
# Power Function
def calculate_power(base, exponent):
    return base ** exponent
```

---

## 🧪 Challenges Faced

* Difficulty managing Python indentation in nested logic
* Confusion about mutable vs immutable data types
* Initial challenges in navigating Jupyter/Colab notebooks and understanding markdown formatting

### ⚖️ How They Were Resolved:

* Referred to official Python documentation and online tutorials (W3Schools, Programiz)
* Practiced small problems repeatedly to build confidence
* Took notes and revisited concepts through example-driven learning

---

## 📖 Learning Outcome

* Solidified understanding of Python programming fundamentals
* Gained practical experience in control structures and loops
* Strengthened problem-solving skills with custom functions and logic
* Learned to build and structure small functional Python scripts

---

## 📈 Next Steps (Week 2 Goals)

* Introduction to **NumPy** and **Pandas** libraries
* Learn array manipulation and DataFrame operations
* Explore CSV/Excel dataset handling
* Begin performing filtering, sorting, grouping, and aggregation on real data

---

## 📁 Repository Structure

```
὜ week1/
├── 📓 NextGen_week1_task1.ipynb
├── 📓 NextGen_week1_task2.ipynb
├── 📄 Internship Weekly Report week1.docx
└── 📄 README.md
```

---

## 🚨 Note

> This repository contains beginner-friendly examples to help understand Python fundamentals through practical implementation. Feel free to explore the notebooks and adapt the code for your learning.
