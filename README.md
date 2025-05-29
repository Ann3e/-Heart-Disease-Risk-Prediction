# ❤️ Heart Disease Risk Prediction with Custom C4.5 Decision Tree & Random Forest

This project predicts **heart disease risk** using a **custom implementation** of the **C4.5 Decision Tree algorithm**, and extends it into a **Random Forest ensemble**. It supports both categorical and continuous features and is benchmarked against scikit-learn's models.

---

## 🩺 Project Goal

To predict whether a patient is at risk of heart disease based on medical attributes like age, blood pressure, cholesterol, and more. We build and evaluate interpretable machine learning models from scratch to understand how decisions are made — without relying entirely on black-box libraries.

---

## 🔍 Key Features

- Built custom **C4.5 Decision Tree** using **Gain Ratio** for accurate, interpretable splits.
- Extended the tree into a **Random Forest ensemble** with **bagging** and **random feature selection**.
- Compared performance with standard models from `scikit-learn`.
- Tuned hyperparameters like `max_depth` and `min_samples` using grid search.

---

## 🧠 Results (Accuracy)

| Model                      | Accuracy |
|---------------------------|----------|
| Scikit-learn Decision Tree| 84.4%    |
| Custom Decision Tree      | 91.7%    |
| Scikit-learn Random Forest| 89.6%    |
| Custom Random Forest      | 93.6%    |

📈 *The custom models outperform standard library versions thanks to careful gain ratio handling and feature splits.*


##  Requirements

numpy
pandas
scikit-learn
matplotlib
seaborn



