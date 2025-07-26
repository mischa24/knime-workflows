# 🧮 KNIME – Assignment 1: GroupBy Average per Marital Status

## 📌 Objective

This workflow calculates the **average age** for each category of **marital status** using the `bank-full.csv` dataset.

---

## ⚙️ Steps

1. **Read CSV File** (`bank-full.csv`)
2. **Select Columns**: `marital`, `age`
3. **GroupBy Node**: 
   - Group by `marital`
   - Aggregate function: **Mean** on `age`
4. **View Results** using the **Interactive Table**

---

## 📸 Screenshots

### Workflow

![Workflow](../1.svg)

### Output Table

![Results](../2.svg)

---

## 📁 Files

- `erg_1_KNIME.knwf` – KNIME workflow file
- `1.svg` – workflow structure
- `2.svg` – resulting table

---

## 🛠 Tools

- KNIME Analytics Platform
- GroupBy, CSV Reader, Interactive Table
