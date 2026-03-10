# Student Performance Prediction with PyTorch

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1gqFJ0BtYg13xcIS3e0zqaUaahwlwzgAi?usp=sharing)
[![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue)](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression)
This project applies linear regression in PyTorch to predict student performance using the Kaggle **Student Performance** dataset. It includes data loading, preprocessing, train-test splitting, feature scaling, model training, evaluation, and result visualization.

## Features

- Linear regression implemented in PyTorch
- Data preprocessing and categorical encoding
- Feature standardization
- Model training and loss tracking
- Performance evaluation using MSE, RMSE, MAE, and R²
- Visualization of training loss and predictions

## Dataset

**Dataset:** Student Performance  
**Source:** Kaggle  
**Identifier:** `nikhil7280/student-performance-multiple-linear-regression`

## Technologies Used

- Python
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- KaggleHub

## Project Structure

```text
student-performance-pytorch-regression/
├── notebook.ipynb
├── requirements.txt
└── README.md
```

## Results

The model achieved strong regression performance, with a high R² score and low prediction error on the test set. This suggests that linear regression is an effective baseline model for this dataset.

### How to Run

Install the required packages:

```bash
pip install torch pandas numpy scikit-learn matplotlib kagglehub
```

Then open and run the notebook in Jupyter Notebook or VS Code.

Author

Rostam Sodagari