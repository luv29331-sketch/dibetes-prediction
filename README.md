# Diabetes Risk Prediction System

## Internship Project

A machine-learning classification project based on the supplied PIMA diabetes dataset. The project uses a **linear Support Vector Machine (SVM)** after feature standardization.

### Dataset
- Records: 768
- Features: 8
- Target: `Outcome`
- `0` = Non-Diabetic
- `1` = Diabetic

### Technology Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

### Workflow
1. Load `diabetes.csv`
2. Inspect and analyze the data
3. Separate features and target
4. Standardize numerical features using `StandardScaler`
5. Perform stratified 80/20 train-test split
6. Train a linear SVM classifier
7. Evaluate with accuracy, confusion matrix and classification report
8. Demonstrate a sample prediction

### Reproducible Result
Using the notebook configuration (`test_size=0.2`, `stratify=Y`, `random_state=2`, `SVC(kernel="linear")`):
- Training accuracy: 0.7866
- Test accuracy: 0.7727

### Project Files
- `Diabetes_Risk_Prediction_System.ipynb` — main implementation
- `diabetes.csv` — supplied dataset
- `Diabetes_Risk_Prediction_Report.docx` — project report
- `Diabetes_Risk_Prediction_Presentation.pptx` — presentation

### Disclaimer
This is an academic/internship machine-learning project. It is not a medical diagnostic system and should not be used for clinical decisions.
