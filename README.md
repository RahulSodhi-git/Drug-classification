# Drug Classification

A supervised **multi-class classification** model that predicts which drug a patient
should be prescribed from their clinical features (age, sex, blood pressure,
cholesterol, sodium-to-potassium ratio). Part of a multi-sector deep-learning /
machine-learning portfolio (healthcare sector).

---

## Approach

1. **EDA** — explore the feature distributions and class balance across drug types.
2. **Preprocessing** — encode categorical features (sex, BP, cholesterol) and scale
   numeric ones.
3. **Modelling** — train and compare scikit-learn classifiers to predict the drug
   class, evaluated with a train/test split.
4. **Evaluation** — accuracy and classification report on held-out data.

**Dataset:** `drug200.csv` — 200 patient records with the target column `Drug`.

---

## Getting started

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook Drugclassification.ipynb
```

Run the cells top to bottom to reproduce the analysis and model.

---

## Repository layout

```
Drugclassification.ipynb   # EDA → preprocessing → model → evaluation
drug200.csv                # dataset (200 patient records)
```

---

## Tech stack

**Python** · **scikit-learn** · **pandas / NumPy** · **matplotlib / seaborn**
