# Alzheimer's Disease Classification

This repository contains a Jupyter Notebook for classifying Alzheimer's disease using machine learning techniques. The project demonstrates a complete workflow, from data preprocessing and feature selection to model training and evaluation.

## Contents

- **Data Preprocessing:**
  - Loaded the dataset (`alzheimers_disease_data.csv`).
  - Dropped irrelevant or less informative columns such as `PatientID`, `Ethnicity`, `EducationLevel`, `Gender`, and `DoctorInCharge`.

- **Feature Selection:**
  - Implemented feature selection techniques using `f_classif`, `mutual_info_classif`, and `chi2`.
  - Scaled the features using `StandardScaler` and `MinMaxScaler` where necessary.

- **Modeling:**
  - Built and trained a Decision Tree Classifier using the processed features.
  - Split the dataset into training and test sets for evaluation.

- **Evaluation:**
  - Used metrics such as accuracy and classification reports to assess model performance.
  - Employed cross-validation using K-Fold to ensure the robustness of the model.

## Prerequisites

To run this notebook, you need to have the following Python libraries installed:

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `scikit-learn`
- `shap`

You can install the required libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn shap
```

## Usage

1. **Clone this repository.**
2. **Open the `Classification.ipynb` notebook.**
3. **Run the cells sequentially to preprocess the data, train the model, and evaluate its performance.**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
