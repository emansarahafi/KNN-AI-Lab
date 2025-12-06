# K-Nearest Neighbors (KNN) AI Lab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/emansarahafi/KNN-AI-Lab/blob/main/LAB_KNN_EmanSarahAfi.ipynb)

## Overview

A comprehensive data mining lab exploring customer churn prediction using the K-Nearest Neighbors (KNN) classification algorithm. This project analyzes a telecom industry customer dataset to predict churn rates based on various customer attributes and usage patterns.

## Dataset

The project uses a customer churn dataset from a fictional telecom firm that includes:

- **Long-distance usage** patterns
- **Data usage** statistics
- **Monthly revenue** information
- **Service offerings** and subscriptions
- **Additional services** purchased by customers

The dataset focuses on customers with phone accounts and combines multiple data sources into a unified CSV file.

## Learning Objectives

After completing this lab, you will gain:

- Understanding of **data preprocessing** techniques for mixed variable types (numeric, categorical, ordinal)
- Practical knowledge of implementing the **K-Nearest Neighbors algorithm**
- Skills in **hyperparameter tuning** (selecting optimal K value)
- Ability to **evaluate model performance** using various metrics
- Experience working with **real-world telecom data**

## Project Structure

```
KNN-AI-Lab/
│
├── LAB_KNN_EmanSarahAfi.ipynb    # Main Jupyter notebook with analysis
├── churndata.csv                  # Customer churn dataset
├── README.md                      # Project documentation
└── LICENSE                        # License information
```

## Key Steps

1. **Data Import and Exploration**
   - Load customer churn data
   - Examine data structure and features
   - Remove unnecessary features (IDs, duplicate metrics)

2. **Data Preprocessing**
   - Identify variable types (binary, categorical, ordinal, numeric)
   - Encode categorical variables appropriately
   - Handle ordinal features
   - Normalize/standardize numeric features

3. **Model Development**
   - Split data into training and testing sets
   - Implement K-Nearest Neighbors classifier
   - Experiment with different K values

4. **Model Evaluation**
   - Assess model performance using multiple metrics
   - Analyze prediction accuracy
   - Visualize results

## Requirements

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
```

## Usage

### Run Locally

1. Clone the repository:

```bash
git clone https://github.com/emansarahafi/KNN-AI-Lab.git
cd KNN-AI-Lab
```

2. Install required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the Jupyter notebook:

```bash
jupyter notebook LAB_KNN_EmanSarahAfi.ipynb
```

### Run on Google Colab

Click the badge at the top of this README to open the notebook directly in Google Colab.

## License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

## Acknowledgments

- Dataset based on a fictional telecom firm for educational purposes
- Developed as part of an Artificial Intelligence course
