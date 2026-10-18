 Breast Cancer Classification Using Decision Tree and K-Nearest Neighbors

 Overview
- Compared two supervised machine learning algorithms: Decision Tree and K-Nearest Neighbors (KNN).
- Used the Breast Cancer Wisconsin dataset from Scikit-learn.
- Objective: Classifying tumour samples as malignant or benign and comparing model performance.

 Dataset
- Source: Scikit-learn
- Samples: 569
- Features: 30 numerical features
- Classes: Malignant and benign
- Train-test split: 80% training, 20% testing
- Random state: 42

 Methodology
1. Loaded the dataset using Scikit-learn.
2. Split the data into training and testing sets.
3. Standardized features for KNN.
4. Trained a Decision Tree classifier.
5. Trained a KNN classifier with (k=5).
6. Evaluated both models using accuracy, precision, recall, F1-score, and confusion matrices.

 Results

| Metric | Decision Tree | KNN |
|---|---:|---:|
| Accuracy | 94.74% | 94.74% |
| Precision (weighted) | 94.74% | 94.74% |
| Recall (weighted) | 94.74% | 94.74% |
| F1-score (weighted) | 94.74% | 94.74% |
| Correct predictions | 108/114 | 108/114 |

Confusion matrix for both models:


[[40  3]
 [ 3 68]]


 Key Findings
- Both models achieved **94.74% test accuracy**.
- Both correctly classified 108 of the 114 test samples.
- The models disagreed on 6 individual predictions.
- Each model was correct on 3 of those 6 disagreements.
- Identical evaluation scores do not necessarily mean models make identical predictions.

 Limitations
- Evaluation used a single train-test split.
- Only two classification algorithms were compared.
- Cross-validation and hyperparameter tuning were not performed.
- Results may vary with different data splits.

 Tools and Technologies
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
