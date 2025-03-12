# ML-Final
### NOTICE: The following work is the original creation of Marko Tyhansky and is not permitted for use without consent of original author.
The updated R Markdown version of my Machine Learning Final

This project applies various machine learning techniques to two datasets: 
1. **Breast Cancer Classification** (benign vs. malignant)
2. **Red Wine Quality Prediction**

---

## 1. Breast Cancer Classification
### **Dataset:** `breast-cancer-wisconsin.csv`
### **Goal:** Predict whether a tumor is **benign (2) or malignant (4)**

### **Models Used:**
- **K-Nearest Neighbors (K-NN)**
- **Decision Trees & Random Forests**
- **Logistic Regression**
- **LDA & QDA**
- **Support Vector Machine (SVM)**

### **Best Model:**
- **SVM** achieved the highest accuracy (**98.05%**), making it the best classifier.

---

## 2. Red Wine Quality Prediction
### **Dataset:** `winequality-red.csv`
### **Goal:** Predict wine quality scores

### **Models Used:**
- **Linear Regression**
- **Decision Trees & Random Forests**
- **Boosting**
- **Neural Networks**

### **With vs. Without PCA:**
- PCA was applied to reduce dimensions.
- **Best Model:** Random Forest (**RMSE = 0.063**) performed best **without PCA**.

---

## 3. K-Means Clustering
- Implemented **K-Means (K=2) manually** to demonstrate clustering skills.

---

## Summary
- **SVM** was best for breast cancer classification.
- **Random Forest (without PCA)** was best for wine quality prediction.
- **PCA improved model stability** but didn’t always improve accuracy.

This project showcases **classification, regression, PCA, and clustering** techniques using R.
