📧 Email Spam or Ham Classification

This repository contains the implementation of Experiment 3 for the Machine Learning Algorithms Laboratory (ICS1512).
The goal is to classify emails as Spam or Ham using Naive Bayes, KNN, and SVM and compare their performance.

📌 Objectives

Preprocess email text data (cleaning, vectorization, train-test split).

Implement:

Naive Bayes variants: BernoulliNB, MultinomialNB, GaussianNB

K-Nearest Neighbors (KNN) with different k values and tree structures

Support Vector Machine (SVM) with multiple kernels (linear, polynomial, RBF, sigmoid)

Compare models using:

    Accuracy

    Precision

    Recall

    F1 Score

    Confusion Matrix

    ROC-AUC

Perform Cross-validation for model robustness.

📚 Libraries Used

    Python 3.x

    Numpy

    Pandas

    Scikit-learn

    Matplotlib

    Seaborn

📊 Results

🔹 Naive Bayes Variants

| Model         | Accuracy | Precision | Recall | F1 Score |
| ------------- | -------- | --------- | ------ | -------- |
| BernoulliNB   | 0.8899   | 0.8843    | 0.8290 | 0.8558   |
| MultinomialNB | 0.8950   | 0.9424    | 0.7813 | 0.8543   |
| GaussianNB    | 0.8197   | 0.7001    | 0.9485 | 0.8056   |

🔹 KNN (different k values)

Best performance at k=5 with Accuracy = 0.8993, F1 Score = 0.8705.

🔹 SVM Kernels

RBF Kernel performed best with Accuracy ≈ 92.6% and F1 Score ≈ 0.90.

📝 Observations

    Naive Bayes: Simple, efficient, works well with text data.

    KNN: High accuracy at low k but computationally heavier.

    SVM (RBF kernel): Best overall performance, good for non-linear decision boundaries.

✅ Conclusion

Best Model: SVM with RBF kernel (Accuracy ≈ 92.7%).

Trade-offs:

    Naive Bayes → Fast, scalable.

    KNN → High accuracy but slower for large datasets.

    SVM → Balanced choice (accuracy + robustness).
