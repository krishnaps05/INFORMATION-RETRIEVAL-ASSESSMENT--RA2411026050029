SMS Spam Detection Using Machine Learning

Project Overview

This project uses machine learning to classify SMS messages as Spam or Ham (Legitimate).

Methodology

Loaded and cleaned a dataset containing 5,169 SMS messages.

Preprocessed the text and used TF-IDF vectorization to convert messages into numerical features.

Split the dataset into training and testing sets.

Trained four algorithms: Decision Tree, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Naive Bayes.

Evaluated the models using accuracy, precision, recall, F1-score, confusion matrices, and execution time.

Conducted a what-if experiment by changing the alpha parameter of Naive Bayes.

Best Model Results

Support Vector Machine (SVM)

Accuracy: 98.26%

Spam F1-score: 92.74%

Technologies Used

Python, Google Colab, Pandas, NumPy, Scikit-learn, TF-IDF, Matplotlib, and Seaborn.

Conclusion

The project demonstrates how machine learning can identify spam messages. SVM achieved the best overall performance among the four models tested.

Google Colab Notebook Link:

         https://colab.research.google.com/drive/16pL6BQ8kbfoupnnxBnMwfhJFsEOmAUnY?usp=sharing

