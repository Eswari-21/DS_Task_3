# DS_Task_3

# Project Overview
This project applies Support Vector Machine (SVM) and XGBoost models to two datasets: the Iris Dataset and the Breast Cancer Dataset. The goal is to demonstrate how both classification algorithms perform on these datasets and compare their predicted results to the true class distributions. The results are visualized to highlight the accuracy and effectiveness of both models.

# Datasets Used
### Iris Dataset: Contains measurements of sepals and petals for three species of iris flowers, and the task is to classify them into their respective species.

### Breast Cancer Dataset: Contains features derived from breast cancer biopsy samples, and the task is to classify the tumors as malignant or benign.

Models Implemented
### Support Vector Machine (SVM): A supervised learning algorithm that finds the optimal hyperplane for classification tasks. Here, the linear kernel is used to classify the datasets.

### XGBoost: A gradient boosting algorithm that excels at classification tasks, especially with structured/tabular data.

# Functionality
The project loads both datasets, splits them into training and testing sets, and then trains both models (SVM and XGBoost) on the training data. After that, predictions are made on the test set, and the true vs. predicted class distributions are visualized in bar charts to compare the models’ performance.

# Visualizations
For each dataset, class distributions of both true and predicted labels are plotted. This allows for a visual inspection of how well each model is performing in comparison to the actual class distribution.

## Key Steps
Data Loading: Iris and Breast Cancer datasets are loaded.

Model Training: Both SVM (with a linear kernel) and XGBoost models are trained on the training data.

Prediction and Comparison: Predictions are made on the test data and compared with the true labels.

Visualization: Bar charts showing true vs. predicted class distributions for each model and dataset.

# Expected Outputs
The final output includes four bar charts:

SVM - Iris Dataset

SVM - Breast Cancer Dataset

XGBoost - Iris Dataset

XGBoost - Breast Cancer Dataset

These charts display the comparison between the true class distributions and the predicted class distributions.

