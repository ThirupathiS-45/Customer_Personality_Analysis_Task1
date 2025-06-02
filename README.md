# 🧼 Data Cleaning in Python (Google Colab)

This project demonstrates how to clean and prepare a raw dataset using **Python in Google Colab**. The dataset contained:
- Missing values
- Duplicate records
- Date columns in incorrect formats
- Inconsistently formatted categorical data

---

## 📂 Dataset Description

The raw dataset was uploaded as a `.csv` file with **tab-separated values**. It included the following issues:
- `Income` had missing values
- `Dt_Customer` was stored as strings
- `Education` and `Marital_Status` contained inconsistent capitalization and whitespace
- Duplicate rows were present

---

## 🚀 Setup and Tools Used

- Google Colab
- Python 3
- Pandas library

---

## 🔧 Data Cleaning Steps

### 1. Import Libraries

```python
import pandas as pd
