# One Last Train - Kaggle

[Kaggle Source](https://www.kaggle.com/competitions/onelasttrain/overview)

---

## Description
- Given the medical dataset. The objective is to determine of the said patient have to return/ readmitted.
- Also if readmitted, have to determine number of time they would be readmitted.
- Target variable is readmitted_NO.

## Challenge
- You are encouraged to only use __Clustering__ methods. Using _classifiers_ is frowned upon.

---

## My Procedure

### Cleaning

- The dataset has _inconsistent_ empty values. To tackle that, a simple panda replace would do the trick.
- Data Columns with too many NaN s will skew the metrics. To remove them, a simple column wise % inspection of NaN s will give how many ineffective columns we have.
- These columns (with less than 20% data) are dropped.
