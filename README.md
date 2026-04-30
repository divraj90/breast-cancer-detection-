# Breast Cancer Classification

**Author:** Divyanshu

## Overview
This project demonstrates a complete workflow for classifying breast cancer tumors as benign or malignant using a neural network. The process includes data preprocessing, exploratory data analysis (EDA), visualization, model building, training, evaluation, and prediction using the Breast Cancer Wisconsin dataset.

## Dataset
- The dataset used is the Breast Cancer Wisconsin (Diagnostic) dataset.
- It contains features computed from digitized images of fine needle aspirate (FNA) of breast masses.
- The target variable is `diagnosis` (0 = benign, 1 = malignant).

## Project Workflow

### 1. Data Loading & Cleaning
- The dataset is loaded using pandas.
- Unnecessary columns (`Unnamed: 32`, `id`) are dropped.
- Checked for missing values and data types.

### 2. Exploratory Data Analysis (EDA)
- Displayed the first few rows and checked the shape of the data.
- Examined the distribution of the target variable (`diagnosis`).
- Used descriptive statistics to summarize the data.
- Grouped data by diagnosis to compare feature means.

### 3. Data Visualization
- Used seaborn and matplotlib for:
  - Count plots of diagnosis distribution.
  - Distribution plots for all features.

### 4. Data Preprocessing
- Encoded the target variable (`diagnosis`) using LabelEncoder.
- Split the data into features (X) and target (Y).
- Performed train-test split (80% train, 20% test).
- Standardized features using StandardScaler for better model performance.

### 5. Model Building
- Built a neural network using TensorFlow and Keras:
  - Input layer: 30 neurons (one for each feature)
  - Hidden layer: 20 neurons, ReLU activation
  - Output layer: 2 neurons, sigmoid activation (for binary classification)
- Compiled the model with Adam optimizer and sparse categorical cross-entropy loss.

### 6. Model Training & Evaluation
- Trained the model for 10 epochs with validation split.
- Visualized training and validation accuracy.
- Evaluated model accuracy on the test set.

### 7. Prediction & Inference
- Used the trained model to predict on new data points.
- Converted prediction probabilities to class labels.
- Provided a sample prediction for a single data point.

## How to Run
1. Ensure you have the required libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `tensorflow`.
2. Place the dataset CSV file in the correct path (update the path in the notebook if needed).
3. Open and run the notebook cells sequentially.
4. Review the outputs, visualizations, and model performance.

## Key Files
- `Breast_Cancer_Classification.ipynb`: Main Jupyter notebook containing all code, analysis, and results.

## Results
- The neural network achieves high accuracy in classifying tumors as benign or malignant.
- Visualizations help understand feature distributions and model performance.

## Author
Divyanshu

---

Feel free to use or modify this project for your own learning or research purposes!
