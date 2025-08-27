# String Operations in Pandas

## Overview
This notebook demonstrates **vectorized string operations** in **Pandas**, focusing on how to efficiently manipulate and analyze string data using built-in functions and regular expressions.

The examples provided are practical and demonstrate how to clean, filter, and transform text data in a DataFrame for data preprocessing and analysis.

---

## Notebook Overview

### **Vectorized String Operations**
- Introduction to vectorized string methods in `pandas.Series.str`.
- Explanation of why vectorization improves performance over Python loops.

### **Common Functions**
- Overview of frequently used functions like:
  - `.str.lower()`, `.str.upper()`
  - `.str.strip()`, `.str.replace()`
  - `.str.contains()`, `.str.len()`
  - `.str.startswith()`, `.str.endswith()`

### **Filtering**
- Using `str.contains()` and boolean indexing for conditional filtering of rows.
- Real-world examples for text pattern matching and filtering datasets.

### **Applying Regular Expressions**
- Introduction to regex and how to integrate it with `pandas` string functions.
- Use cases:
  - Extracting specific text patterns
  - Cleaning complex strings
  - Tokenizing strings using regex patterns

