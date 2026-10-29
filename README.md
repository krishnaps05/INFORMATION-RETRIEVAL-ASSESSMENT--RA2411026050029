
# 📩 SMS Spam Detection Using Machine Learning

## 📌 Project Overview
This project uses **Machine Learning** to classify SMS messages as **Spam** (unwanted messages) or **Ham** (legitimate messages).

## ⚙️ Project Workflow
- **Data Preprocessing:** Cleaned and prepared a dataset containing 5,169 SMS messages.
- **Feature Extraction:** Used **TF-IDF Vectorization** to convert text into numerical features.
- **Model Training:** Trained four algorithms:
  - Decision Tree
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Multinomial Naive Bayes
- **Model Evaluation:** Compared models using accuracy, precision, recall, F1-score, confusion matrices, and execution time.
- **Parameter Tuning:** Tested different alpha values for Naive Bayes to study their impact on performance.

## 🏆 Best Model Results

**Support Vector Machine (SVM)** achieved the best performance.

| Metric | Score |
|---|---:|
| Accuracy | **98.26%** |
| Spam Precision | **98.29%** |
| Spam Recall | **87.79%** |
| Spam F1-score | **92.74%** |

## 🛠️ Technologies Used
- **Language:** Python
- **Platform:** Google Colab
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Technique:** TF-IDF Vectorization

## ✅ Conclusion
This project demonstrates how machine learning can automatically identify spam messages. Among the four models tested, **SVM achieved the highest accuracy of 98.26%**.

## 🔗 Google Colab Notebook
          https://colab.research.google.com/drive/16pL6BQ8kbfoupnnxBnMwfhJFsEOmAUnY?usp=sharing
