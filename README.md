# Fake-News-Projecct
This project focuses on building a machine learning model to classify news articles as either real or fake. The dataset includes metadata and content-related features, such as title, text, subject, and publication date. After preprocessing and feature engineering (e.g., removing null values, text cleaning, encoding categorical variables), I tested multiple classification algorithms including:

- Logistic Regression
- k-Nearest Neighbors (kNN)
- Decision Trees (CART)
- Random Forests
- Naive Bayes

Model performance was evaluated using accuracy, confusion matrices, and cross-validation. Ultimately, I developed an ensemble model using XGBoost as a meta-learner, which achieved 90.25% accuracy on the validation set.

This project demonstrates the importance of feature selection, encoding strategies, and ensemble learning in improving classification accuracy — especially in high-stakes tasks like misinformation detection.
