# SGD_Classifier

Implementation of SGD Classifier with Logloss and L2 regularization from scratch without using sklearn. This helps in understanding the concepts deeply.

**The Stochastic Gradient Descent (SGD) classifier** is a machine learning algorithm commonly used for large-scale classification tasks. It's an optimization technique that iteratively updates the model's parameters by minimizing a loss function using small subsets (batches) of the training data. SGD is particularly useful for handling large datasets, as it processes data in mini-batches, making it computationally efficient and capable of handling high-dimensional feature spaces.

**Log Loss (Logarithmic Loss)** is a widely used loss function for classification problems. It measures the difference between predicted probabilities and actual class labels. The goal is to minimize log loss, which penalizes large errors more heavily than smaller ones. Log loss is especially suitable for probabilistic models, as it quantifies the uncertainty associated with predictions. Lower log loss indicates better model performance, and it is often used in evaluating the quality of predicted probabilities in binary and multiclass classification.

**L1 regularization, also known as Lasso regularization** (Least Absolute Shrinkage and Selection Operator), is a technique used in machine learning to prevent overfitting and feature selection. It is similar to L2 regularization (Ridge regularization) but has a slightly different effect on the model's coefficients.

In L1 regularization, a penalty term is added to the loss function that is proportional to the absolute values of the model's coefficients (weights). The goal of L1 regularization is to encourage the model to reduce some of the coefficients to exactly zero, effectively performing feature selection by eliminating less important features from the model. This can lead to a sparse model where only a subset of the features is retained, making the model simpler and potentially more interpretable.

**L2 regularization, also known as Ridge regularization**, is a technique used to prevent overfitting in machine learning models. It adds a penalty term to the loss function that discourages large values for the model's coefficients (weights). L2 regularization helps to keep the model's weights small, making the model more robust and reducing the potential for overfitting. The strength of the L2 regularization is controlled by a hyperparameter λ (lambda). Higher values of λ lead to stronger regularization and smaller weights.
