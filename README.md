# DATA1030 Final Project: Which Resume Attributes Drive Job Callbacks?

## Overview
This repository contains the code, reports, and resources for my DATA1030 final project, which analyzes the impact of various resume attributes on job callbacks. The project employs machine learning techniques to predict callback rates and identify the most influential resume features.

The primary goals of this project include:
- Building a reproducible machine learning pipeline to analyze resume data.
- Identifying key resume features that drive job callbacks.
- Visualizing and interpreting model results to provide actionable insights.

---

## Dataset
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/utkarshx27/which-resume-attributes-drive-job-callbacks). It includes **4,870 rows** and **30 columns**, detailing attributes of resumes and job postings, as well as a target variable (`received_callback`) indicating whether a callback was received.

### Key Features
- **Resume Features**: Years of experience, education level, resume quality, and special skills.
- **Job Features**: Job city, industry, type, and specific requirements.
- **Demographic Features**: Race, gender, and additional personal attributes.

---

## Directory Structure
```plaintext
.
├── data/                 # Data directory
│   ├── preprocessed_example_data.csv  # Example preprocessed data
│   ├── resume.csv                     # Original dataset
├── figures/              # Plots and visualizations
├── results/              # Model outputs, predictions, and evaluation metrics
│   ├── all_predicted_vs_true_LogisticRegression.csv
│   ├── all_predicted_vs_true_RandomForestClassifier.csv
│   ├── all_predicted_vs_true_SVC.csv
│   ├── all_predicted_vs_true_XGBClassifier.csv
│   ├── LogisticRegression_models.pkl
│   ├── RandomForestClassifier_models.pkl
│   ├── SVC_models.pkl
│   └── XGBClassifier_models.pkl
├── report/               # Final report in PDF format
├── src/                  # Python scripts and Jupyter notebooks
│   └── DATA1030Project.ipynb
├── LICENSE               # License file for the repository
└── README.md             # This file
```

## Installation

To reproduce the results in this repository, you need Python 3.9 or later and the following packages:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `xgboost`
- `kaggle` (for downloading the dataset)

### Setting Up the Environment
To set up and run this project locally, follow these steps:

1. **Clone the repository**:
```bash
git clone https://github.com/anyfruit/Key-Resume-Attributes-Impacting-Job-Callbacks.git
cd Key-Resume-Attributes-Impacting-Job-Callbacks
```

2. **Create a virtual environment and install dependencies**:
```bash
python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
pip install -r requirements.txt
```

3. **Run the Jupyter Notebook**:
```bash
jupyter notebook src/DATA1030Project.ipynb
```

---

## Key Results
- **Model Performance**: XGBoost outperformed other models with an F1 score of 0.2414.
- **Feature Importance**: Key features identified include *years of experience*, *resume quality*, and *special skills*.
- **SHAP Analysis**: Visualizations highlighted how resume attributes influence predictions.

Full findings are detailed in the final report: [DATA1030 Final Project Report](report/DATA1030%20Final%20Project%20Report.pdf).

---

## License
This project is licensed under the **MIT License**. See the LICENSE file for details.

---

## Acknowledgments
- Dataset Source: [Kaggle](https://www.kaggle.com/datasets/utkarshx27/which-resume-attributes-drive-job-callbacks)
- Course: DATA1030 - Hands-On Data Science at Brown University