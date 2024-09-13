# Learning_Machine_Cookbook
All about Machine Learning

## When to use which Machine learning Algorithm

| Algorithm Type | Examples | When to Use | Pros | Cons |
|----------------|----------|-------------|------|------|
| Linear Regression | Ordinary Least Squares, Ridge Regression, Lasso Regression | - Predicting numerical values<br>- Understanding feature importance | - Simple and interpretable<br>- Fast to train and predict | - Assumes linear relationship<br>- Sensitive to outliers |
| Logistic Regression | Binary Logistic Regression, Multinomial Logistic Regression | - Binary classification<br>- Multi-class classification<br>- Probability estimation | - Provides probability scores<br>- Relatively simple and fast | - Assumes linear decision boundary<br>- May underperform with complex relationships |
| Decision Trees | CART, ID3, C4.5 | - Both classification and regression<br>- When interpretability is important | - Easy to understand and interpret<br>- Handles non-linear relationships | - Prone to overfitting<br>- Can be unstable |
| Random Forest | - | - Complex classification or regression tasks<br>- When you have a large feature space | - Resistant to overfitting<br>- Handles large feature spaces well | - Less interpretable than single decision trees<br>- Computationally intensive |
| Support Vector Machines (SVM) | Linear SVM, Kernel SVM | - Binary classification<br>- Regression (SVR)<br>- When you have a clear margin of separation | - Effective in high-dimensional spaces<br>- Versatile through different kernel functions | - Not suitable for large datasets<br>- Sensitive to choice of kernel and parameters |
| K-Nearest Neighbors (KNN) | - | - Classification and regression<br>- When you have a small to medium-sized dataset | - Simple and intuitive<br>- No training phase | - Computationally expensive for large datasets<br>- Sensitive to irrelevant features |
| Neural Networks | Feedforward NN, CNN, RNN, LSTM | - Complex pattern recognition tasks<br>- Image and speech recognition<br>- Natural language processing | - Can model complex non-linear relationships<br>- Highly flexible and powerful | - Require large amounts of data<br>- Computationally intensive<br>- Often considered a "black box" |
| K-Means Clustering | - | - Unsupervised learning for finding groups<br>- Customer segmentation<br>- Image compression | - Simple and fast<br>- Works well on evenly sized, globular clusters | - Needs to specify number of clusters beforehand<br>- Sensitive to initial conditions and outliers |
| Principal Component Analysis (PCA) | - | - Dimensionality reduction<br>- Feature extraction<br>- Data visualization | - Reduces complexity while preserving variance<br>- Can help with multicollinearity | - Linear transformation only<br>- May lose important information |
| Gradient Boosting | XGBoost, LightGBM, CatBoost | - Both classification and regression<br>- When you need high performance | - Often achieves state-of-the-art results<br>- Handles different types of data well | - Can be prone to overfitting<br>- Computationally intensive |

Remember that the choice of algorithm often depends on the specific characteristics of your data, the size of your dataset, the interpretability requirements, and computational constraints. It's often beneficial to try multiple algorithms and compare their performance for your specific problem.
