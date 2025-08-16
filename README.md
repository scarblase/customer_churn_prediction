# Customer Churn Prediction - Neural Network

A machine learning project predicting bank customer churn using deep learning, achieving **86.5% accuracy** with actionable business insights.

## Overview

Built a neural network model to identify customers likely to churn, enabling proactive retention strategies. The model analyzes customer demographics, account behavior, and transaction patterns to predict churn probability.

**Key Results:**

- 86.5% prediction accuracy
- Identified high-risk customer segments
- Quantified potential business impact ($2.3M annual savings)

## Technical Stack

- **Python**: Data analysis and modeling
- **TensorFlow/Keras**: Neural network implementation
- **Pandas/NumPy**: Data manipulation
- **Scikit-learn**: Preprocessing and evaluation
- **Matplotlib/Seaborn**: Data visualization

## Model Architecture

```
Neural Network:
├── Input Layer (13 features)
├── Hidden Layer 1 (128 neurons, ReLU, Dropout 0.3)
├── Hidden Layer 2 (64 neurons, ReLU, Dropout 0.2)
├── Hidden Layer 3 (32 neurons, ReLU)
└── Output Layer (Sigmoid activation)
```

## Key Features

- **Feature Engineering**: Created business-relevant metrics (balance per product, customer value segments)
- **Data Preprocessing**: One-hot encoding, standardization, handling categorical variables
- **Model Optimization**: Early stopping, learning rate scheduling, dropout regularization
- **Business Analysis**: Customer segmentation, ROI calculations, strategic recommendations

## Performance Metrics

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 86.5% |
| Precision | 84.2% |
| Recall    | 78.9% |
| F1-Score  | 81.4% |
| AUC-ROC   | 0.892 |

## Business Impact

- **High-risk customers identified**: 2,000 (20% of customer base)
- **Potential annual savings**: $2.3M through targeted retention
- **Key insights**: German customers and single-product users show highest churn risk

## Setup

```bash
pip install -r requirements.txt
jupyter notebook customer_churn_prediction_portfolio.ipynb
```

## Files

- `customer_churn_prediction_portfolio.ipynb` - Main analysis notebook
- `requirements.txt` - Dependencies
