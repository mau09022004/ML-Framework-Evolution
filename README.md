# Machine Learning Framework Evolution
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-FA0F00?style=for-the-badge&logo=jupyter&logoColor=white)
![PDF](https://img.shields.io/badge/PDF-FF0000?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
## Overview
This project focuses on solving a predictive task from a Kaggle competition. It follows a complete Machine Learning pipeline, including data preprocessing, exploratory data analysis, feature engineering, model development, and evaluation while systematically comparing and improving model performance across Scikit-learn, PyTorch/TensorFlow, and XGBoost/LightGBM/CatBoost through an experiment-driven ML process to predict target.
## Dataset
The dataset for this competition (both train and test) was generated from a deep learning model, thus it is a synthetic dataset that you will never find a duplication at anywhere else. Feature distributions are close to, but not exactly the same, as the original data used to train that model.
There are 3 files:
- train.csv - the training dataset; target is the continuous target
- test.csv - the test dataset; your objective is to predict target for each row
- sample_submission.csv - a sample submission file in the correct format
## Project Structure
```
ML-Framework-Evolution/
│
├── data/
│   └── data link.txt              # Link to Kaggle dataset
│
├── report/
│   └── 22127260_22127400.pdf     # Report of project
│
├── src/
│   ├── Preprocessing.ipynb       # Data cleaning & feature preparation
│   ├── Normalization.ipynb       # Feature scaling and transformation
│   ├── Phase 1.ipynb             # Phase 1 - ML with Scikit-learn
│   ├── Phase 2.ipynb             # Phase 2 - Deep Learning (PyTorch/TensorFlow)
│   ├── Phase 3.1.ipynb           # Phase 3 - Boosting (part 1)
│   └── Phase 3.2.ipynb           # Phase 3 - Boosting (part 2)
│
└── README.md                    
```
## Technologies Used
Programming & Environment: Python, Jupyter Notebook 
- Data Processing & Analysis: Pandas, NumPy
- Machine Learning & Preprocessing: Scikit-learn (preprocessing, model selection, evaluation metrics)
- Deep Learning: TensorFlow
- Gradient Boosting Frameworks: LightGBM, CatBoost
- Hyperparameter Optimization: Optuna
- System Monitoring & Utilities: psutil, time, os
## Pipeline
There are 5 steps:
1. Data preparation: load data, handle missing values, encode categorical features, and apply feature scaling.
2. Exploratory Data Analysis (EDA): explore data distributions, relationships, and detect potential issues.
3. Modeling: build and train models by using multiple frameworks.
4. Optimization: Tune model using Optuna.
5. Model evaluation & iteration: evaluate by using suitable metrics.
## How to run
 Clone all repository:
 ```bash
git clone https://github.com/mau09022004/ML-Framework-Evolution.git
cd ML-Framework-Evolution
```
## Author
* **Bùi Công Mậu**: [mau09022004](https://github.com/mau09022004)
* **Thái Hữu Thọ**: [huuThoTT](https://github.com/huuThoTT)
