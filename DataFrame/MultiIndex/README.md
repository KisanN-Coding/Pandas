# Multi Index in Pandas

## Overview

This notebook provides a **comprehensive guide to working with MultiIndex objects** in the `pandas` library. It explains how to handle hierarchical indexing in both `Series` and `DataFrame`, which is essential for analyzing and managing complex datasets efficiently.

---

## Key Topics Covered

### 1. Understanding Dimensions
- Why `Series` is considered a **1D object**.
- Why `DataFrame` is considered a **2D object**.

### 2. Creating MultiIndex Series
- Using **tuples** as index values (basic approach).
- Correct creation of MultiIndex objects with:
  - `pd.MultiIndex.from_tuples()`
  - `pd.MultiIndex.from_product()`
- Accessing and slicing data efficiently with multi-level keys.

### 3. MultiIndex Operations
- Slicing and indexing with multiple levels of the hierarchy.
- Converting between Series and DataFrame using:
  - `.unstack()` → Converts MultiIndex Series into a DataFrame.
  - `.stack()` → Converts a DataFrame back into a MultiIndex Series.

### 4. MultiIndex in DataFrames
- Constructing a MultiIndex `DataFrame`.
- Performing selection, filtering, and reshaping operations on hierarchical datasets.

---

## Use Cases
MultiIndexing is especially useful for:
- Time-series data analysis with multiple dimensions.
- Grouped or aggregated data, such as **department-year combinations**.
- Pivot tables with multi-level row and column indexes.
