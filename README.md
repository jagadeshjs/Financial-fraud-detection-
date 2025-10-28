Financial fraud detection has become increasingly important in today’s digital world, where millions of transactions occur every second. While traditional machine learning models like Decision Trees, SVMs, and even Graph Neural Networks (GNNs) have shown promise, they often fail to capture both temporal dependencies and complex relational structures between transactions.

To overcome this limitation, this project proposes a hybrid model that integrates Temporal Graph Neural Networks (TGNN) with Long Short-Term Memory (LSTM) and Generative Adversarial Networks (GANs). This architecture effectively detects evolving and hidden fraud behaviors in financial transaction data.

Key Features :

Combines TGNN + LSTM + GAN for dynamic fraud detection.

Uses L1-Regularized Logistic Regression for feature selection.

Handles imbalanced data using SMOTE.

Evaluates performance with Precision, Recall, F1-Score, AUC, and Accuracy.

Benchmarked against traditional models: Decision Tree, SVM, GNN, and TGNN.
