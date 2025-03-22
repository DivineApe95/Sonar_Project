# Sonar_Project

## Overview
This repository contains a machine learning model that classifies sonar signals as either **rocks (R)** or **mines (M)**. The model is trained using **Logistic Regression** and evaluates its performance on a dataset of sonar signal readings.

## Files in this Repository

### 1. `sonar.ipynb`
- Jupyter Notebook containing the full pipeline:
  - Data loading and preprocessing
  - Exploratory Data Analysis (EDA)
  - Training a **Logistic Regression** model
  - Evaluating model performance
  - Making predictions with new input data
  - Visualizing training vs. testing accuracy

### 2. `data.csv`
- The dataset used in this project:
  - Each row represents a sonar signal with **numerical frequency readings**.
  - The last column contains the labels:
    - **"R"** for rock
    - **"M"** for mine

## Installation
To run this project locally, install the required dependencies:
```bash
pip install numpy pandas scikit-learn matplotlib
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/sonar-classification.git
   cd sonar-classification
   ```
2. Open and run `sonar.ipynb` in Jupyter Notebook or Google Colab.

## Model Training & Evaluation
- The dataset is split into **90% training** and **10% testing**.
- The model is evaluated using **accuracy metrics**.
- A predictive system is implemented for making real-time predictions on new sonar readings.

