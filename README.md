# Adey Innovations Fraud Detection Project

## Overview

This project develops a machine learning model to detect fraudulent transactions for Adey Innovations. It includes data analysis, feature engineering, and model building with experiment tracking.

## Project Structure
content_copy
download
Use code with caution.
Markdown

├── data # Contains the raw data files
├── notebooks # Jupyter notebooks for EDA, feature engineering, and modeling
├── scripts # Python scripts for custom functions and pipeline stages
├── scalers # Folder for storing model scalers
├── feature_store
├── model # Best performing model
├── mlflow_runs # MLflow run tracking metadata
├── README.md # This file
└── requirements.txt # Project dependencies

## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone [repository URL]
    cd [repository directory]
    ```

2.  **Set up a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    venv\Scripts\activate  # On Windows
    ```

3.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **(Optional) Set up Mlflow:**

    ```bash
    mlflow ui --host 0.0.0.0
    ```

5.  **Run the notebooks:**

    ```bash
    jupyter notebook exploratory_data_analysis.ipynb
    jupyter notebook feature_engineering.ipynb
    jupyter notebook modeling.ipynb
    jupyter notebook modle_explanation.ipynb
    ```

## Contributor

## Mikias Befekadu 


