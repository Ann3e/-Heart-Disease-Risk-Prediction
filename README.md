# 🧠 Custom Decision Tree & Random Forest (C4.5)

This project implements a custom **Decision Tree** classifier using the **C4.5 algorithm**, with support for both categorical and continuous features. It is extended into a **Random Forest** ensemble with bootstrap sampling and random feature selection. The models are benchmarked against scikit-learn's implementations.

---

## 🚀 Project Highlights

- 🔍 Built custom Decision Tree (C4.5) from scratch using **Gain Ratio** for splitting
- 🌳 Extended to a Random Forest ensemble using **bagging** and **random feature selection**
- ⚙️ Hyperparameter tuning (`max_depth`, `min_samples`) via grid search

---

## Performance
| Model                   | Accuracy |
|------------------------|----------|
| scikit-learn Decision Tree | 84.4%    |
| Custom Decision Tree       | 91.7%    |
| scikit-learn Random Forest | 89.6%    |
| Custom Random Forest       | 93.6%    |

