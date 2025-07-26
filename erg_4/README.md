# 🧠 KNIME – Assignment 4: Ensemble of Three Models

## 📌 Objective

This project builds upon a provided KNIME workflow (`eLearning_regression_II_part_2.knwf`) and focuses on extracting and understanding the **ensemble logic** applied via a `Math Formula` node.

---

## ⚙️ Process Overview

1. **Load the original workflow** provided in course material
2. **Inspect the final Math Formula node**, which combines predictions from **three models**
3. **Extract the formula** used for ensemble averaging

---

## 🧮 Ensemble Expression

In the `Math Formula` node (under the *Math Expression* tab), the following formula is used to combine predictions:

```plaintext
($Prediction (quality)$ + $Prediction (quality (#1)$) + $Prediction (quality (#2)$)) / 3

Math Formula Node Configuration
<img width="865" height="641" alt="image" src="https://github.com/user-attachments/assets/7ebc473a-f04a-49b1-9df1-57e0077c331c" />

Workflow Overview
<img width="865" height="561" alt="image" src="https://github.com/user-attachments/assets/36484887-257d-47c7-b764-6152ad82f92e" />

