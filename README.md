# AI-ML-Internship-Task-11

# SVM Breast Cancer Classification

## Objective
Build and tune an SVM model to classify breast cancer tumors as malignant or benign.

## Dataset
- Sklearn Breast Cancer Dataset (load_breast_cancer)

## Steps Performed
- Data loading and inspection
- Feature scaling using StandardScaler
- Baseline SVM (Linear Kernel)
- SVM with RBF Kernel
- Hyperparameter tuning using GridSearchCV
- Model evaluation with confusion matrix and classification report
- ROC Curve and AUC calculation
- Saved trained pipeline

## Best Model
- Kernel: RBF
- Tuned using GridSearchCV

## Results
- High classification accuracy
- ROC AUC Score included in notebook
- Saved model file: svm_breast_cancer_pipeline.pkl

## Files
- svm_breast_cancer.ipynb
- svm_breast_cancer_pipeline.pkl
- README.md
