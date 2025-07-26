# 🤖 KNIME – Assignment 3: Ensemble Regression

## 📌 Objective

This project builds a simple **ensemble regression model** using two base learners. It evaluates performance and calculates a combined prediction.

---

## 📊 Steps

1. **CSV Reader**: Load dataset (e.g. wine quality data)
2. **Partitioning**: Split data into training and test sets
3. **Train Two Models**:
   - `Simple Regression Tree Learner`
   - `Regression Predictor`
4. **Predict + Score**:
   - Use `Numeric Scorer` to evaluate MAE, RMSE, etc.
5. **Join Predictions**:
   - Combine both models' predictions using a `Joiner`
6. **Ensemble Formula**:
   - Use `Math Formula` to compute the average prediction:
     ``` 
     ($Prediction (quality)$ + $Prediction (quality (#1)$) / 2
     ```

---

## 📸 Visuals

### Workflow

![Workflow](../erg_3/erg_3_knime.png)

### Output Metrics

![Metrics](../erg_3/3.svg)

### Prediction Join

![Join](../erg_3/erg_3_export.svg)

---

## 📁 Files

- `erg_3_knime.png` – workflow overview
- `erg_3_export.svg` – joined predictions
- `3.svg` – model evaluation metrics

---

## 🛠 Tools

- KNIME Analytics Platform
- Regression Learners, Joiners, Math Formula, Numeric Scorer
