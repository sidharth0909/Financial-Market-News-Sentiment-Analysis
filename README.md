# Financial Market News Sentiment Analysis

## 📌 Project Overview
Financial Market News Sentiment Analysis is a machine learning project that analyzes financial news articles to determine their sentiment (positive, negative, or neutral). The goal is to leverage sentiment analysis to assist in predicting market movements, developing investment strategies, and managing risks effectively.

---

## 📂 Dataset
- **Source**: YBI Foundation Datasets
- **Columns**:
  - `Date`: Date of news articles
  - `Label`: Sentiment of the news (0 = Negative, 1 = Positive)
  - `News 1 - News 25`: 25 headlines per day

---

## 🛠️ Technologies Used
- **Programming Language**: Python
- **Machine Learning Libraries**: Scikit-learn, Pandas, NumPy
- **NLP Techniques**: Bag of Words (CountVectorizer)
- **Model**: Random Forest Classifier

---

## 🔍 Feature Engineering
1. **Text Preprocessing**:
   - Combined all news headlines for each day into a single text entry.
   - Converted text to lowercase and tokenized it.
2. **Vectorization**:
   - Used `CountVectorizer` to convert text into numerical features (Bag of Words).

---

## 🎯 Model Training & Evaluation
- **Train-Test Split**: 70% training, 30% testing
- **Model Used**: Random Forest Classifier (`n_estimators = 200`)
- **Performance Metrics**:
  - Accuracy: **50.6%**
  - Precision & Recall:
    - **Positive News**: Recall **73%**, Precision **52%**
    - **Negative News**: Recall **26%**, Precision **46%**

---

## ⚡ Challenges & Improvements
- **Feature Engineering Enhancements**:
  - Use **TF-IDF** for better text representation.
  - Implement **word embeddings (Word2Vec, BERT, or FastText)** for semantic understanding.
- **Algorithm Optimization**:
  - Try **Logistic Regression, XGBoost, or LSTMs** for better classification.
- **Data Balancing**:
  - Implement **SMOTE** or collect more labeled data to handle class imbalance.

---

## 🚀 How to Run the Project
### 1️⃣ Install Dependencies
```bash
pip install pandas numpy scikit-learn
```
### 2️⃣ Run the Python Script
```bash
python sentiment_analysis.py
```

---

## 🤝 Contributions
Contributions are welcome! Feel free to fork the repository, create an issue, or submit a pull request.

---

## 📜 License
This project is licensed under the MIT License.

---

## 📧 Contact
For queries or collaboration, reach out via [LinkedIn](https://www.linkedin.com/in/sidharth-saholiya).

