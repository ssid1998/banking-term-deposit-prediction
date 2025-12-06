# Banking Term Deposit Prediction

This project analyzes direct marketing campaigns (phone calls) of a Portuguese banking institution. The goal is to predict whether a client will subscribe to a term deposit based on demographic and behavioral data.

## Project Overview

This repository contains a comprehensive analysis and a machine learning model to solve the classification problem described in the dataset.

### Data

The dataset (`banking_data.csv`) contains 45,211 records with 18 attributes, including:
- **Client Demographics**: Age, Job, Marital Status, Education.
- **Financial Status**: Credit Default, Balance, Housing Loan, Personal Loan.
- **Campaign Details**: Contact Type, Last Contact Day/Month, Duration, Number of Contacts.
- **Previous Campaign History**: Days since last contact, Poutcome (outcome of previous campaign).
- **Target Variable**: `y` (has the client subscribed to a term deposit? - 'yes'/'no').

### Analysis & Modeling

The key analysis is performed in `analysis.ipynb`, which includes:
1.  **Exploratory Data Analysis (EDA)**: Visualizing distributions of age, job, marital status, and other features.
2.  **Data Preprocessing**: Handling categorical variables (One-Hot Encoding) and target variable conversion.
3.  **Model Building**: Training a Random Forest Classifier to predict term deposit subscriptions.
4.  **Evaluation**: Assessing model performance using Accuracy and Classification Reports.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

### Installation

1.  Clone this repository.
2.  Install dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
    ```

### Usage

1.  Open the notebook:
    ```bash
    jupyter notebook analysis.ipynb
    ```
2.  Run the cells to view the analysis and model results.

## Folder Structure

- `analysis.ipynb`: The main Jupyter Notebook with code and visualizations.
- `banking_data.csv`: The dataset used for analysis.
- `Banking/`: Contains additional project files and scripts.
- `Problem Statement & Data Description.pdf`: Detailed description of the problem and data dictionary.
