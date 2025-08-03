Employee Salary Prediction – ML Web App

This project is a machine learning web application built using **Streamlit** to predict whether an employee earns more than 50K annually based on features like age, education, occupation, etc.
Overview
-  Predicts employee salary category (>50K or ≤50K)
-  Includes visual analysis of the dataset (pie charts, count plots, heatmap)
-  Compares multiple ML models:
  - Logistic Regression
  - K-Nearest Neighbors
  - MLP Classifier
- Accepts user inputs for prediction through an interactive form
  
  # Files and Structure
├── app.py # Main Streamlit app
├── model_comparison.py # ML model training and evaluation
├── data/
│ └── adult 3.csv # Dataset used
├── assets/ # Visualizations (optional)
├── requirements.txt # Python packages

## Dataset

- **Name**: UCI Adult Income Dataset
- **Target**: `income` ( >50K or ≤50K )
- **Rows**: ~48,000+
- 
## ⚙️ Tech Stack

- **Python**, **Pandas**, **Scikit-learn**
- **Streamlit** for UI
- **Seaborn**, **Matplotlib** for visualization

## 🚀 How to Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
