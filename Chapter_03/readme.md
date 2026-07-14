# 📘 Chapter 3: Strings

<div align="center">

![Strings](https://img.shields.io/badge/Topic-Strings_%26_Methods-teal?style=for-the-badge)

*Unlock the power of text manipulation! In this chapter, we explore Strings, how to slice them, and powerful built-in methods to format text.*

</div>

---

## 🌟 Key Concepts

### 🧵 1. What is a String?
A **String** is a sequence of characters enclosed in quotes. You can use single, double, or even triple quotes (for multi-line strings).
```python
name1 = 'Arun'       # Single quotes
name2 = "Arun"       # Double quotes
name3 = '''Arun'''   # Triple quotes
```

### ✂️ 2. String Indexing and Slicing
Strings are ordered sequences, meaning every character has a specific position (index) starting from `0`.

* **Indexing**: Accessing a single character.
  ```python
  name = "Python"
  print(name[0])  # Output: 'P'
  ```
* **Slicing**: Extracting a portion of the string.
  ```python
  # syntax: string[start_index : end_index]
  print(name[0:3]) # Output: 'Pyt' (excludes index 3)
  ```
* **Negative Indexing**: Accessing characters from the end of the string (`-1` is the last character).

### 🛠️ 3. String Functions (Methods)
Python provides numerous built-in functions to work with strings:
- `len(name)`: Returns the length of the string.
- `name.endswith("on")`: Returns `True` if it ends with "on".
- `name.count("o")`: Counts occurrences of a character/substring.
- `name.capitalize()`: Capitalizes the first letter.
- `name.replace(old, new)`: Replaces a word with another word.

### 🏃‍♂️ 4. Escape Sequences
Used to insert characters that are illegal or have special meaning in a string.
- `\n` : New line
- `\t` : Tab space
- `\'` : Single quote
- `\\` : Backslash

---

## 📂 Files in this Chapter

| File | Description |
| :--- | :--- |
| 🐍 **[`01_intro_to_String.py`](./01_intro_to_String.py)** | Introduction to strings and concatenation. |
| 🐍 **[`02_negative_slicing.py`](./02_negative_slicing.py)** | Demonstrates how negative indices work. |
| 🐍 **[`03_string_function.py`](./03_string_function.py)** | Exploring `len`, `endswith`, `capitalize`, etc. |
| 🐍 **[`04_escape_seq.py`](./04_escape_seq.py)** | How to use `\n`, `\t`, and other escape characters. |
| 🐍 **[`find_index.py`](./find_index.py)** | Finding the index of a specific character/substring. |
| 🐍 **[`replace_text.py`](./replace_text.py)** | Using the `replace()` string method. |
| 🐍 **[`string.py`](./string.py)** | General string operations overview. |
| 🐍 **[`word_join.py`](./word_join.py)** | Example of joining/concatenating words. |

---

## 🚀 Ready for Practice?

Time to manipulate some text!

👉 **[Go to Chapter 3 Practice Set (Chapter_03 PS)](../Chapter_03%20PS)**
