# Breast Cancer Classification

This project demonstrates a basic machine learning workflow for classifying breast cancer tumors as benign or malignant using the Breast Cancer Wisconsin Diagnostic dataset.

## Project Objective

The goal is to understand how a medical classification dataset can be cleaned, explored, prepared, and used to train a neural network model for binary classification.

## Tech Stack

- Python
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The project uses the Breast Cancer Wisconsin Diagnostic dataset. The features are computed from digitized images of fine needle aspirate samples of breast masses.

Target:

- benign
- malignant

## Repository Structure

```text
.
├── Breast_Cancer_Classification.ipynb
└── README.md
```

## Workflow

1. Load the dataset
2. Remove unnecessary columns
3. Check missing values and data types
4. Explore target distribution and feature statistics
5. Visualize feature distributions
6. Encode the target variable
7. Split the data into train and test sets
8. Scale numerical features
9. Train a neural network classifier
10. Evaluate model performance
11. Run sample predictions

## How To Run

Install the required packages:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn tensorflow jupyter
```

Open the notebook:

```bash
jupyter notebook Breast_Cancer_Classification.ipynb
```

Run the cells from top to bottom.

## What I Learned

- How to inspect and clean a classification dataset
- How to split data for training and testing
- Why feature scaling is important for neural networks
- How to build a basic Keras model
- How to evaluate a binary classification model

## Limitations

- This is a learning project, not a medical diagnostic system.
- More model comparison is needed.
- More evaluation metrics should be added, such as confusion matrix, precision, recall, and F1 score.

## Future Improvements

- Add confusion matrix and classification report
- Compare Logistic Regression, Random Forest, and neural network models
- Add a requirements file
- Add saved charts from the notebook
- Add a short explanation of the most important features

