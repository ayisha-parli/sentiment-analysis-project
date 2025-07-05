# Sentiment Analysis using VADER & RoBERTa 💬🤖

This project performs sentiment analysis on text data using both rule-based (NLTK's VADER) and transformer-based (RoBERTa) models. It includes exploratory data analysis (EDA), visualizations, and a side-by-side comparison of model performance.

---

## 📌 Features

- 📊 **EDA** to understand text data distributions
- 🧠 **VADER (NLTK)** for fast, rule-based sentiment prediction
- 🤖 **RoBERTa (Transformer model)** for deep learning-based sentiment classification
- 📈 **Performance comparison** between VADER and RoBERTa
- 📉 **Visualizations** of sentiment distribution and model output

---

## 📁 Files in This Repository

- `sentimental_project.ipynb` — Main Jupyter notebook with all code and outputs
- `README.md` — Project documentation

---

## 🛠️ Libraries Used

- `nltk`
- `transformers` (Hugging Face)
- `tqdm`
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

---

## 🔍 EDA Highlights

- Word count distribution
- Text length analysis
- Class balance and sentiment spread

---

## 🧪 Models Used

### ✅ VADER (Valence Aware Dictionary for Sentiment Reasoning)
- From `nltk.sentiment.SentimentIntensityAnalyzer`
- Rule-based sentiment analysis
- Best for short texts, social media data

### ✅ RoBERTa (Pre-trained Transformer)
- Fine-tuned for sentiment classification
- Context-aware and powerful on longer, complex sentences

---

## 📊 Score Comparison

| Metric         | VADER      | RoBERTa    |
|----------------|------------|------------|
| Accuracy       | ~78%       | ~91%       |
| F1 Score       | ~0.75      | ~0.90      |
| Speed          | ⚡ Fast     | 🐢 Slower  |
| Context Aware  | ❌ No       | ✅ Yes     |

> These are sample scores — update with your actual results if available.

---

## 🚀 How to Run

1. Open the notebook in **Google Colab**
2. Install dependencies if needed:
   ```bash
   pip install nltk transformers pandas matplotlib seaborn scikit-learn
Run all cells from top to bottom

Compare predictions from VADER and RoBERTa

👩‍💻 Author
Ayisha
2nd Year CSE Student | Passionate about AI/ML
📍 Thrissur, India

