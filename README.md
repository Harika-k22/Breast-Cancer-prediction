Built binary classification models using Random Forest and K-Nearest Neighbors (K=3)
on the Breast Cancer Wisconsin Diagnostic dataset (UCI ML Repo, ID:17) to predict malignant vs. benign tumors.

Preprocessed data with label encoding and feature scaling.
Split dataset into 70/30 train-test sets.
Achieved >95% accuracy; evaluated with precision, recall, F1-score, and confusion matrix.
Demonstrated effectiveness of tree-based and distance-based classifiers for medical diagnosis.
Tools: Python, scikit-learn, pandas, seaborn, matplotlib.
Also included cross-validation as breast cancer prediction project, cross-validation is especially important because:
The dataset might be small or imbalanced (more benign than malignant or vice versa).
Make sure your model generalizes well to unseen patients, not just the split you initially chose.
It reduces the risk that your evaluation metrics (accuracy, confusion matrix, etc.) are biased by a lucky or unlucky train-test split.
