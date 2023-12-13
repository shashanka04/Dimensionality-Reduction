# Dimensionality-Reduction
*Objective:*
Reduce the number of features in a dataset while preserving its essential information.
Address issues related to the curse of dimensionality, improve computational efficiency, and potentially enhance model performance.

**Principal Component Analysis (PCA):**

Objective:

Transform the original features into a new set of orthogonal features called principal components.
Capture the most variance in the data with the first component, and subsequent components capture maximum variance orthogonal to the previous ones.

Steps:

>Standardization

>Covariance Matrix Computation

>Eigenvalue Decomposition

>Selecting Principal Components

>Projection

**Linear Discriminant Analysis (LDA):**

Objective:

Maximize the separation between different classes in a dataset.
Find the linear combination of features that best discriminates between classes.

Key Points:
Unlike PCA, LDA is supervised and uses class labels to guide the transformation.
It aims to maximize the between-class scatter and minimize the within-class scatter.

Various Dimensionality Techniques:

*Missing Value Ratio:*

Evaluate features based on the percentage of missing values.
Remove or impute features with a high percentage of missing values.

*Low Variance Filter:*

Identify features with low variance across instances.
Low-variance features may not provide much information and can be removed.

*Random Forest Feature Importance:*

Use a random forest algorithm to assess the importance of each feature.
Rank features based on their contribution to model accuracy.

*High Correlation Filter:*

Identify and remove highly correlated features.
Correlated features might provide redundant information.

Note: These techniques (missing value ratio, low variance filter, random forest, high correlation filter) are often used in the context of feature selection and preprocessing to enhance model performance and reduce overfitting. 
They are not considered dimensionality reduction techniques in the same sense as PCA and LDA, as they focus on selecting or removing specific features rather than transforming the entire feature space.

In summary, dimensionality reduction techniques like PCA and LDA aim to transform the feature space, while various filters and methods like missing value ratio,
low variance filter, random forest, and high correlation filter are employed for feature selection and preprocessing in unsupervised machine learning.
