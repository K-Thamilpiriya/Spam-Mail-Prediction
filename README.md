# Spam Mail Prediction using Machine Learning
Spam mail prediction is a machine learning application that automatically classifies emails or messages as Spam or Ham (Not Spam). This project uses TF-IDF feature extraction and Logistic Regression to build an efficient and accurate spam detection system.
# Objectives
* To build a machine learning model that detects spam messages.
* To preprocess and vectorize text data using TF-IDF.
* To train and evaluate a Logistic Regression classifier.
* To achieve high accuracy and good generalization.
# Dataset used from kaggle website
<a href="https://github.com/K-Thamilpiriya/Spam-Mail-Prediction/blob/main/Spam_Mail_Prediction.ipynb">Mail_dataset</a><br>
<a href="https://colab.research.google.com/drive/1-kUCrmIduVFBvRmgQcLG-uwnDN2uGmDG">Colab link</a>
# Methodology
<img width="943" height="694" alt="Screenshot 2026-01-11 145511" src="https://github.com/user-attachments/assets/4d593018-8b70-4ac0-a058-d7891f34a3cf" />

* Data Preprocessing
    * Converted text to lowercase.
    * Removed stopwords.
    * Converted labels (spam/ham) to numerical values.
* Feature Extraction
    * Used TF-IDF Vectorizer to convert text into numerical feature vectors.
    * Resulting data represented as a sparse matrix.
* Model Training
    * Algorithm: Logistic Regression.
    * Data split into training and testing sets.
* Model Evaluation.
    Ev* aluation Metric: Accuracy.
# Results
Training Data	96.77%
Testing Data	96.68%
# Analysis
Training and testing accuracies are very close.
Indicates no overfitting.
Model generalizes well to unseen data.
# Discussion
The high accuracy achieved by the model demonstrates the effectiveness of combining TF-IDF vectorization with Logistic Regression for spam detection. The minimal difference between training and testing accuracy confirms that the model has learned meaningful patterns without overfitting. This approach is computationally efficient and well-suited for real-world applications.
# Conclusion
The spam mail prediction system successfully classifies messages with high accuracy. With a testing accuracy of 96.68%, the model proves to be reliable and efficient. This system can be effectively used in real-world email or SMS spam filtering applications.
