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
