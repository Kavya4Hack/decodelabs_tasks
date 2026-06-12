# Advanced EDA & Feature Engineering on Housing Dataset

## Project Overview

This project focuses on performing Advanced Exploratory Data Analysis (EDA) and Feature Engineering on a Housing Dataset.

The objective is to transform raw housing data into a clean and machine-learning-ready dataset through data preprocessing, outlier treatment, feature engineering, and statistical analysis.

---

## Dataset Information

- Dataset: Housing Dataset
- Records: 545
- Features: 13

### Features

- price
- area
- bedrooms
- bathrooms
- stories
- mainroad
- guestroom
- basement
- hotwaterheating
- airconditioning
- parking
- prefarea
- furnishingstatus

---

## Project Workflow

### 1. Data Loading
- Loaded dataset using Pandas
- Examined structure and feature types

### 2. Exploratory Data Analysis
- Dataset overview
- Statistical summary
- Feature distributions

### 3. Missing Value Analysis
- Checked for missing values
- Demonstrated imputation techniques

### 4. Outlier Detection
- Used IQR (Interquartile Range) method
- Visualized outliers using boxplots

### 5. Feature Engineering
Created the following new features:

- Total Rooms
- Price Per Square Foot
- House Score

### 6. Correlation Analysis
- Generated correlation heatmap
- Studied relationships between variables

### 7. Data Preprocessing
- Label Encoding of categorical variables
- Dataset cleaning and preparation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Project Structure

Project_1_EDA_Feature_Engineering/

├── data/

│ ├── Housing.csv

│ └── cleaned_data.csv

├── notebooks/

│ └── EDA_Project.ipynb

├── screenshots/

├── report/

├── README.md

├── requirements.txt

└── .gitignore

---

## Results

- Successfully performed Advanced EDA
- Detected and handled outliers
- Created meaningful engineered features
- Prepared a machine-learning-ready dataset

---

## Author

Kavya