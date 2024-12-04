<<<<<<< HEAD
# DATA1030 Final Project: Which Resume Attributes Drive Job Callbacks?

## Overview
This repository contains the code and resources for my DATA1030 final project, focused on analyzing which resume attributes influence job callbacks. The project explores machine learning techniques to predict callback rates using a diverse dataset of resume and job attributes.

The primary goals of this project include:
- Applying advanced machine learning techniques to a real-world dataset.
- Evaluating the importance of different resume features in predicting callback likelihood.
- Developing a clear and reproducible machine learning pipeline.

---

## Dataset
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/utkarshx27/which-resume-attributes-drive-job-callbacks). It includes **4,870 rows** and **30 columns**, detailing attributes of resumes and job postings, as well as a target variable (`received_callback`) indicating whether a callback was received.

### Key Features
- **Resume Features**: Education level, years of experience, computer skills, special skills, etc.
- **Job Features**: Industry, type, federal contractor status, equal opportunity employer status, etc.
- **Demographic Features**: Gender, race, and other identifiers.

For more details, refer to the dataset documentation linked above.

---

## Directory Structure
```plaintext
.
├── data/                 # Data directory
│   ├── raw/              # Raw data files (if stored locally)
│   ├── processed/        # Processed data files
├── figures/              # Plots and visualizations
├── results/              # Model outputs, predictions, and evaluation metrics
├── report/               # Final report in PDF format
├── src/                  # Python scripts and Jupyter notebooks
├── .gitignore            # Files and directories to ignore in Git
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
1. **Clone this repository:**

```bash
git clone https://github.com/your-username/DATA1030-Final-Project.git
cd DATA1030-Final-Project
```

2. **Create a virtual environment and activate it:**

```bash
python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
```

3. **Install the required dependencies:**

```bash
pip install -r requirements.txt
```

4. **Add your Kaggle API credentials:**

- Create a `.env` file and include your Kaggle API key to access the dataset.


## Usage

1. **Download the dataset**: Use the following script to download the dataset:

```python
from kagglehub import dataset_download
dataset_download("utkarshx27/which-resume-attributes-drive-job-callbacks")
```
2. **Preprocess the data**: Run the preprocessing scripts in the `src/` directory.

3. **Train and evaluate models**: Use the provided pipeline to train and evaluate the models.


## Key Results

The project's findings are detailed in the final report (`report/DATA1030_Final_Report.pdf`). Highlights include:

- Feature importances computed using SHAP values.
- Comparison of machine learning models (e.g., Logistic Regression, Random Forest, XGBoost).
- Recommendations for improving callback prediction accuracy.

## License
This project is licensed under the **MIT License**. See the LICENSE file for details.

## Acknowledgments
- Dataset Source: Kaggle
- Course: DATA1030 - Hand's On Data Science at Brown University


=======
# DATA1030 Final Project: Which Resume Attributes Drive Job Callbacks?

## Overview
This repository contains the code and resources for my DATA1030 final project, focused on analyzing which resume attributes influence job callbacks. The project explores machine learning techniques to predict callback rates using a diverse dataset of resume and job attributes.

The primary goals of this project include:
- Applying advanced machine learning techniques to a real-world dataset.
- Evaluating the importance of different resume features in predicting callback likelihood.
- Developing a clear and reproducible machine learning pipeline.

---

## Dataset
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/utkarshx27/which-resume-attributes-drive-job-callbacks). It includes **4,870 rows** and **30 columns**, detailing attributes of resumes and job postings, as well as a target variable (`received_callback`) indicating whether a callback was received.

### Key Features
- **Resume Features**: Education level, years of experience, computer skills, special skills, etc.
- **Job Features**: Industry, type, federal contractor status, equal opportunity employer status, etc.
- **Demographic Features**: Gender, race, and other identifiers.

For more details, refer to the dataset documentation linked above.

---

## Directory Structure
```plaintext
.
├── data/                 # Data directory
│   ├── raw/              # Raw data files (if stored locally)
│   ├── processed/        # Processed data files
├── figures/              # Plots and visualizations
├── results/              # Model outputs, predictions, and evaluation metrics
├── report/               # Final report in PDF format
├── src/                  # Python scripts and Jupyter notebooks
├── .gitignore            # Files and directories to ignore in Git
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
1. **Clone this repository:**

```bash
git clone https://github.com/your-username/DATA1030-Final-Project.git
cd DATA1030-Final-Project
```

2. **Create a virtual environment and activate it:**

```bash
python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
```

3. **Install the required dependencies:**

```bash
pip install -r requirements.txt
```

4. **Add your Kaggle API credentials:**

- Create a `.env` file and include your Kaggle API key to access the dataset.


## Usage

1. **Download the dataset**: Use the following script to download the dataset:

```python
from kagglehub import dataset_download
dataset_download("utkarshx27/which-resume-attributes-drive-job-callbacks")
```
2. **Preprocess the data**: Run the preprocessing scripts in the `src/` directory.

3. **Train and evaluate models**: Use the provided pipeline to train and evaluate the models.


## Key Results

The project's findings are detailed in the final report (`report/DATA1030_Final_Report.pdf`). Highlights include:

- Feature importances computed using SHAP values.
- Comparison of machine learning models (e.g., Logistic Regression, Random Forest, XGBoost).
- Recommendations for improving callback prediction accuracy.

## License
This project is licensed under the **MIT License**. See the LICENSE file for details.

## Acknowledgments
- Dataset Source: Kaggle
- Course: DATA1030 - Hand's On Data Science at Brown University


>>>>>>> c9de16082b5f9d8f7e0156dbbfdebb69a92a4baf
For questions or suggestions, feel free to create an issue in this repository or contact me directly.