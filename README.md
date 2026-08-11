# Comprehensive Customer Churn Analysis with Machine Learning

This project presents a complete, end-to-end machine learning workflow for predicting customer churn. The analysis is built using Python, leveraging the powerful pandas, scikit-learn, and matplotlib libraries.

The repository is structured as a Jupyter Notebook (`churn_analysis.ipynb`) that walks through every step of the ML pipeline:

## 📊 Project Overview

The notebook performs a deep analysis on the customer churn dataset, covering:

1.  **Data Loading & Inspection**: Importing the dataset and understanding its initial structure and values.
2.  **Exploratory Data Analysis (EDA)**: Detailed visual analysis including:
    *   Churn rate breakdown by gender and partner status.
    *   Churn patterns across contract types and internet service technologies.
    *   Impact of tenure, monthly charges, and total charges on churn likelihood.
    *   Relationship between payment methods and customer retention.
3.  **Data Preprocessing**: Preparing the data for modeling by:
    *   Handling missing values in `TotalCharges` by imputing with the mean of the column.
    *   Encoding categorical features using One-Hot Encoding (`pd.get_dummies`).
4.  **Feature Engineering**: Creating a `Churn_Yes` binary target variable.
5.  **Model Building & Training**:
    *   Splitting the data into training and testing sets.
    *   Training four distinct classification models:
        *   Logistic Regression
        *   Decision Tree
        *   Random Forest
        *   Support Vector Machine (SVM)
6.  **Model Evaluation**:
    *   Generating detailed classification reports (Precision, Recall, F1-Score, Support).
    *   Visualizing confusion matrices for each model to understand prediction accuracy.

## 🚀 Getting Started

### Prerequisites
Ensure you have the following Python libraries installed:
*   `pandas`
*   `numpy`
*   `matplotlib`
*   `seaborn`
*   `scikit-learn`

You can install them using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Running the Notebook
1.  Clone the repository.
2.  Open the `churn_analysis.ipynb` file in a Jupyter Notebook environment.
3.  Run the cells sequentially to follow the analysis.

## 📂 Repository Structure

*   **`churn_analysis.ipynb`**: The main notebook containing the complete code and analysis.
*   **`customer_churn.csv`** (Assumed to be present in the directory or specified path): The dataset used for the analysis.
*   **`README.md`**: This file, providing an overview of the project.

## 🛠️ Technology Stack

*   **Language**: Python 3.x
*   **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn