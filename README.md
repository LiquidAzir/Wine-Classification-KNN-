# Wine-Classification-KNN-
Simple KNN classification analysis

**Classification Task & Business Problem:**
The task involved developing a KNN classifier to categorize wines into different quality classes. The business problem could be for a wine distributor needing to efficiently categorize their wine inventory for better management and targeted customer segmentation. This classification was based on wine properties like alcohol content, acidity, etc.

**Appropriate Metric & Justification:**
Given the dataset's relatively balanced nature, accuracy was chosen as a primary metric, complemented by the F1-score. The F1-score was relevant due to the slight class imbalance.

**Analysis Summary & Results:**
Data Inspection: I first loaded and inspected the dataset, confirming its structure and class distribution.
Preprocessing: The data was split into features and target variables, followed by standard scaling.
Model Building: I implemented a KNN classifier and used grid search for hyperparameter optimization, focusing on maximizing the F1-score.
Model Evaluation: The optimized model achieved an accuracy of 94.44% and an F1-score of 94.36% on the test set.
These results indicated the model's high efficacy in classifying wines, proving its potential as a valuable tool for the wine distributor’s inventory categorization and customer segmentation efforts.
