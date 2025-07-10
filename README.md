# 🧠 NLP Sentiment Analysis using Machine Learning

This project performs **Sentiment Analysis** on text data using **Natural Language Processing (NLP)** techniques and a **Random Forest Classifier**. It includes a **Streamlit web application** for real-time predictions based on user input.

---

## 🔍 Overview

Sentiment analysis is the process of determining whether a piece of text is **positive**, **negative**, or **neutral**. This project includes:

- Text preprocessing using NLP (tokenization, stopwords removal, stemming)
- Feature extraction using TF-IDF
- Model training using Random Forest
- Web interface with Streamlit to test the model on custom inputs

---

## 🛠️ Technologies Used

- **Python**
- **Streamlit** – for building interactive UI
- **scikit-learn** – ML algorithms (Random Forest)
- **NLTK** – for text preprocessing
- **Pandas & NumPy** – data handling
- **Matplotlib & Seaborn** – visualizations (optional)

---

## 📁 Project Structure

NLP-Sentiment-Analysis/
├── NLP Project 3 - Twitter Sentiment Analysis with Random Forest.ipynb   # Jupyter notebook with full analysis
├── app.py                                                               # Streamlit web app for sentiment prediction
├── twitter_sentiment.csv                                               # Dataset with tweets and sentiment labels
├── README.md                                                            # Project documentation
└── model.pkl (optional)                                                 # Trained Random Forest model (if saved separately)


---

## 📊 Dataset

The project uses a labeled sentiment dataset (e.g., product reviews, tweets).  
Make sure your CSV has at least two columns:

- `text`: the content to analyze
- `label`: the sentiment (Positive, Negative, or Neutral)

---

## ⚙️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/jauwaad0786/NLP-Sentiment-analysis.git
cd NLP-Sentiment-analysis

streamlit run app.py

