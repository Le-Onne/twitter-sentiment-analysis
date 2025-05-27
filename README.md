# 🐦 Twitter Sentiment Analysis

This project uses machine learning and natural language processing (NLP) to classify tweets as positive or negative. It demonstrates how textual data from social media can be preprocessed, vectorized, and modeled to reveal public sentiment trends.

---

## 📊 Project Overview

- **Goal:** Classify tweet sentiment as Positive or Negative  
- **Tech Stack:** Python, Pandas, NLTK, scikit-learn  
- **Vectorization:** CountVectorizer, TF-IDF  
- **Modeling Technique:** Support Vector Machine (SVM)  
- **Evaluation Metrics:** Accuracy, Confusion Matrix, Classification Report

---

## 📁 Project Structure

twitter-sentiment-analysis/
│
├── twitter_sentiment.ipynb # Main notebook
├── README.md # Project summary and instructions

---

## 📦 Libraries Used

- `pandas` for data handling  
- `nltk` for tokenization and text preprocessing  
- `sklearn` for vectorization, model training, and evaluation

---

## 🔍 Dataset

- **Source:** Pre-labeled tweet dataset  
- **Target Column:** `Sentiment` (Positive = 1, Negative = 0)

---

## 🔧 Preprocessing Steps
- Lowercasing and cleaning text  
- Tokenization using NLTK  
- Stopword removal  
- Vectorization with `CountVectorizer` and `TfidfVectorizer`

---

## 🚀 How to Run
1. Clone the repository  
2. Install the required libraries  
3. Open the notebook and run all cells

git clone https://github.com/Le-Onne/twitter-sentiment-analysis.git

---

## ✅ Results

| Model                     | Accuracy | Notes                                |
|--------------------------|----------|--------------------------------------|
| SVM (TF-IDF)             | 71.25%   | Strong performance on text classification using TF-IDF |
| Random Forest (TF-IDF)    | 68.89%   | Moderate accuracy, slightly lower than SVM |
| N-Grams Model            | 68.28%   | Fair performance, weaker on precision |

## 📊 Visualizations

### 📌 Confusion Matrix
Evaluates model predictions vs actual sentiment classes

### 📌 Classification Report
Displays precision, recall, and F1-score for each sentiment

## 🧠 Key Takeaways
- SVM with TF-IDF vectorization achieved the highest accuracy (~71%)
- TF-IDF improves text classification by reducing the weight of common terms
- Text preprocessing (stopword removal, tokenization) significantly affects model quality
- Multiclass classification (Positive, Negative, Neutral) introduces complexity beyond binary sentiment
  
## 🙋‍♂️ Author
**Heng Le-Onne**  
[GitHub Portfolio](https://github.com/Le-Onne)

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).

