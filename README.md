# Session 29 – AIML Text Vectorization

## 👨‍💻 Author

**Aryan Sanjay Chopade**

Computer Engineering Student  
Takshashila Polytechnic, Amravati

---

## 📌 Project Overview

This project focuses on **NLP-based Emotion Text Classification** using different text vectorization techniques and a Multinomial Naive Bayes classifier.

The project includes text preprocessing, feature extraction, model training, accuracy comparison, and model saving.

---

## 🛠️ Techniques Used

- Text Preprocessing
- Bag of Words (BoW)
- N-grams (Unigrams + Bigrams)
- TF-IDF
- Multinomial Naive Bayes
- Train-Test Split
- Accuracy Evaluation
- Joblib Model Saving

---

## 📊 Results

| Method | Accuracy |
|---|---:|
| Bag of Words (Unigrams) | 76.81% |
| Bag of Words (Unigrams + Bigrams) | 72.72% |
| TF-IDF | 66.09% |

### 🏆 Best Method

**Bag of Words (Unigrams)** achieved the highest accuracy of **76.81%**.

---

## 🤖 Sample Prediction

**Input:**  
`i am feeling very happy today`

**Predicted Emotion:**  
`joy`

---

## 📁 Project Files

- `Session29_AIML.ipynb` – Complete project notebook
- `best_model.pkl` – Trained Multinomial Naive Bayes model
- `best_vectorizer.pkl` – Trained CountVectorizer
- `README.md` – Project documentation

---

## 🎯 Conclusion

Different text vectorization techniques were compared for emotion classification. Among the tested methods, **Bag of Words with Unigrams** provided the best accuracy of **76.81%** on the test dataset.
