# 🧠 Task 7 - Support Vector Machines (SVM)

## 🎯 Objective
Use SVMs for linear and non-linear classification using the Breast Cancer dataset.

## 🧰 Tools Used
- Python
- Google Colab
- Scikit-learn
- NumPy
- Matplotlib

## 📊 Steps Performed
1. Loaded the **Breast Cancer dataset** from Scikit-learn.
2. Preprocessed the data and scaled features using `StandardScaler`.
3. Trained two SVM models:
   - Linear Kernel
   - RBF (Non-linear) Kernel
4. Visualized decision boundaries for both models.
5. Tuned hyperparameters using `GridSearchCV`.
6. Evaluated performance with cross-validation and accuracy metrics.

## ⚙️ Key Concepts Learned
- Margin Maximization
- Kernel Trick
- Hyperparameter Tuning
- Cross-validation

## 📈 Results
- **Linear Kernel Accuracy:** ~95%
- **RBF Kernel Accuracy:** ~97%
- Best parameters from Grid Search: `C=1`, `gamma=0.1`, `kernel='rbf'`

## 📤 Submission
GitHub repo link was submitted via the provided Google Form.
