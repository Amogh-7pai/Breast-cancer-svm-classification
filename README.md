# 🩺 Breast Cancer Classification using Support Vector Machines (SVM)

This project applies **Support Vector Machines (SVM)** to classify breast cancer tumors as **malignant** or **benign** using the Breast Cancer dataset. Both **linear** and **RBF kernels** are used, along with hyperparameter tuning and cross-validation for optimal performance.

---

## 📁 Dataset
- **File:** `breast-cancer.csv`
- **Target:** `diagnosis`  
  - M = Malignant (1)  
  - B = Benign (0)

---

## ✅ Project Highlights
- Data cleaning and preprocessing
- Feature scaling using `StandardScaler`
- SVM with **linear** and **RBF** kernels
- Confusion matrix and classification report
- Hyperparameter tuning using **GridSearchCV**
- Cross-validation to assess model performance stability

---

## 🛠️ Libraries Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📊 Results
- High classification accuracy on test data
- RBF kernel achieved better performance for this task
- Hyperparameter tuning improved the model's generalization
- Cross-validation confirmed consistent performance
