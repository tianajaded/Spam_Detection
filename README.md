# Spam Detection via SVM

## Project Overview
This project aims to classify spam emails using Support Vector Machine (SVM) models with both linear and radial kernels. By analyzing the SPAM dataset, we compare the performance of these models in distinguishing between spam and non-spam emails. We perform feature selection, data preprocessing, and model training to achieve this goal.

## Background
SVMs are powerful machine learning algorithms that can be used for binary classification tasks. In this project, we leverage SVMs to classify emails as spam or non-spam. We employ two different kernel functions for SVMs: linear and radial (RBF), to compare their effectiveness.

## Model Training and Evaluation
We trained SVM models using both linear and radial kernels:

- Linear Kernel SVM: Easier to interpret but may struggle with capturing complex, nonlinear relationships.
  
- Radial Kernel SVM: Capable of capturing nonlinear patterns but less interpretable due to its operation in a transformed feature space.
  
# Steps Involved:
1. Data Splitting: The dataset was split into training and test sets.
2. Training: Both SVM models were trained on the training set.
3. Evaluation: Models were evaluated using accuracy, confusion matrices, and other relevant metrics.

# Results
- Linear Kernel SVM:

Offered better interpretability.
Had more false negatives compared to the radial kernel SVM.
Operated in the original feature space, making the influence of each feature on the classification decisions clearer.

-Radial Kernel SVM:

Showed better performance in capturing complex, nonlinear relationships.
Had fewer false negatives, indicating better identification of spam emails.
Operated in a high-dimensional feature space transformed by the radial basis function, making it harder to interpret decision boundaries.

Both models achieved relatively high accuracy, but the radial kernel model demonstrated superior performance in identifying spam emails, highlighting its capability to handle complex data.

## Conclusion
The classification of spam emails using SVM models showcases the effectiveness of machine learning algorithms in binary classification tasks. The choice between linear and radial kernels involves a trade-off between interpretability and performance. The radial kernel is preferable for datasets with complex and nonlinear relationships, while the linear kernel provides easier interpretation.

Conclusion
The classification of spam emails using SVM models showcases the effectiveness of machine learning algorithms in binary classification tasks. The choice between linear and radial kernels involves a trade-off between interpretability and performance. The radial kernel is preferable for datasets with complex and nonlinear relationships, while the linear kernel provides easier interpretation.
