# 📘 Chapter 2: Variables and Data Types

<div align="center">

![Data Types](https://img.shields.io/badge/Topic-Variables_%26_Data_Types-purple?style=for-the-badge)

*Dive into the core of Python programming! Learn how to store, manipulate, and identify different types of data.*

</div>

---

## 🌟 Key Concepts

### 📦 1. Variables and Identifiers
A **Variable** in Python acts like a container that stores data. 

Think of it this way:
- **Red Container** = Sugar
- **Blue Container** = Salt

When we write:
```python
a = 1
```
- `a` is the **identifier** (the label on the container).
- `1` is the **data** (what is inside the container).

### 🧬 2. Primary Data Types
Python automatically figures out what kind of data you are storing. Here are the main types:

| Data Type | Description | Examples |
| :--- | :--- | :--- |
| **Integer (`int`)** | Whole numbers without decimals. | `1`, `-42`, `100` |
| **Float (`float`)** | Numbers with a decimal point. | `1.5`, `-3.14`, `0.0` |
| **String (`str`)** | Text wrapped in quotes (single or double). | `"Hello"`, `'Python'` |
| **Boolean (`bool`)** | Truth values. | `True`, `False` |
| **NoneType (`None`)**| Represents the absence of a value. | `None` |

### 🔍 3. Checking the Type
You can use the built-in `type()` function to inspect the data type of any variable.
```python
x = 3.14
print(type(x))  # Output: <class 'float'>
```

### 📏 4. Rules for Variable Names
To name your variables properly, follow these strict rules:
1. Must start with a **letter** or an **underscore** (`_`).
2. Cannot start with a **number**.
3. Can only contain **alphanumeric characters** and underscores (`A-z`, `0-9`, and `_`).
4. **Case-sensitive** (`Age` and `age` are different).
5. Cannot be a **Python keyword** (e.g., `def`, `class`, `if`).

---

## 📂 Files in this Chapter

| File | Description |
| :--- | :--- |
| 🐍 **[`01_Variables.py`](./01_Variables.py)** | Demonstrates variable declaration and basic arithmetic. |
| 🐍 **[`02_datatypes.py`](./02_datatypes.py)** | Shows various data types and how to check them using `type()`. |
| 🐍 **[`03_rule_variables.py`](./03_rule_variables.py)** | Code examples on valid and invalid variable names. |
| 🐍 **[`04_operators.py`](./04_operators.py)** | Explanation of different arithmetic and logical operators. |
| 📝 **[`notes.txt`](./notes.txt)** | Detailed hand-written notes summarizing this chapter. |

---

## 🚀 Ready for Practice?

Mastered the theory? Jump into the practice set!

👉 **[Go to Chapter 2 Practice Set (Chapter_02 PS)](../Chapter_02%20PS)**
