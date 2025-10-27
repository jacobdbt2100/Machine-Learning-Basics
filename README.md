# Machine Learning Basics

**Normal Distribution**: A normal distribution is a symmetric, bell-shaped distribution where data cluster around the mean.

It’s important in data analysis and machine learning because many statistical methods assume normality and real-world data often approximate this pattern, especially through the Central Limit Theorem.

**Linear Regression**: a statistical method used to model the relationship between a dependent variable and one or more independent varaibles.

**Overfitting**: occurs when a model is too complex and performs too well.

**Confusion Matrix**: a table used to evaluate the performance of a classification model showing the true positives, true negatives, false positives, and false negatives.

## Types of Machine Learning
- Supervised: Predict output using labelled data (e.g., Linear Regression, Logistic Regression, Random Forest, SVM, XGBoost)
  > **Example tasks**: Classification, Regression
- Unsupervised: Discover patterns from unlabelled data (e.g., K-Means, Hierarchical Clustering, PCA)
  > **Example tasks**: Clustering, Dimensionality Reduction
- Semi-supwervised: Use small labelled + large unlabelled data

## Normalization vs Standardization
> `Normalisation` rescales data to a fixed range; `Standardization` rescales data to have a fixed mean and variance. Choose based on algorithm assumptions and feature scale sensitivity.

| Feature      | **Normalization**                      | **Standardization**     |
| ------------ | -------------------------------------- | ----------------------- |
| Purpose      | Scale to a fixed range                 | Scale to mean 0, std 1  |
| Formula      | (x − min) / (max − min)                | (x − μ) / σ             |
| Output Range | Usually 0–1                            | No fixed range          |
| Distribution | Preserved                              | Centered & rescaled     |
| Outliers     | Highly sensitive                       | Moderately sensitive    |
| Best For     | Distance-based & neural network models | Linear models, PCA, SVM |

