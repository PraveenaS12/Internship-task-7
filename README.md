# Task 7 - Support Vector Machines (SVM)

This repository contains my implementation for **Task 7** of the AI & ML Internship under the Ministry of MSME and Elevate Labs. The objective of this task was to apply Support Vector Machines (SVM) for both linear and non-linear classification problems.

## 🔍 Objective
Use SVMs to:
- Perform binary classification
- Visualize decision boundaries
- Tune model hyperparameters
- Evaluate classification performance using cross-validation and metrics

## 🛠 Tools & Libraries
- Python
- Scikit-learn
- NumPy
- Matplotlib
- mlxtend (for visualization)

## 📌 Task Highlights

1. **Data Preparation**
   - Used `make_classification` to generate a synthetic 2D binary dataset

2. **SVM Training**
   - Trained SVM with both linear and RBF kernels
   - Visualized decision boundaries using `plot_decision_regions` and `matplotlib`

3. **Hyperparameter Tuning**
   - Applied `GridSearchCV` to find the best `C` and `gamma` values for RBF kernel

4. **Model Evaluation**
   - Performed 5-fold cross-validation to check generalization
   - Generated confusion matrix and classification report

5. **Support Vectors Visualization**
   - Highlighted support vectors in the plotted decision boundary

## 📈 Results
- Achieved 96% accuracy on the synthetic dataset using the optimized RBF kernel
- Clear visualization of decision boundary and support vectors

## 🔗 Deliverables
- Jupyter Notebook (`SVM.ipynb`)
- Screenshots of evaluation and plots
- Hyperparameter tuning results
- Classification metrics

---

## ✅ How to Run

1. Install dependencies:
```bash
pip install scikit-learn matplotlib mlxtend
