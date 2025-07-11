# customer-clissification
Classification project to predict customer using ML models
# Cell Sample Classification

This project classifies cell samples as benign or malignant using supervised machine learning algorithms.

---

## 🎯 Objective

To predict whether a cell is benign or malignant based on microscopic characteristics.

---

## 📊 Dataset

- Source: Cell Samples CSV dataset (similar to UCI ML Breast Cancer Dataset)
- Features include: `Clump Thickness`, `Uniformity of Cell Size`, `Bare Nuclei`, etc.
- Target variable: `Class` (2 = Benign, 4 = Malignant)

---

## 🧠 Models Used

- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors
- Decision Tree
- Accuracy and Confusion Matrix used for evaluation

---

## 📈 Results

- Best performing model: SVM with ~96% accuracy
- Confusion matrix showed strong class separation

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## 🔜 Future Work

- Try ensemble methods (RandomForest, XGBoost)
- Hyperparameter tuning
- Handle class imbalance if present

