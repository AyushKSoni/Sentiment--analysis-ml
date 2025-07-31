# 🧠 Sentiment Analysis - ML Part

This repository contains the **Machine Learning part** of a Sentiment Analysis project. The model classifies customer reviews into **positive** or **negative** sentiment using **Natural Language Processing (NLP)** techniques and a **Naive Bayes classifier**.

## 📂 Files Included

- `predict.py` — Python script to load the model/vectorizer and make predictions.
- `model.pkl` — Trained Naive Bayes classifier saved using `pickle`.
- `vectorizer.pkl` — TF-IDF vectorizer used to transform input text.
- `README.md` — Project overview and usage.

## 🧪 Technologies Used

- Python
- Scikit-learn
- NLTK
- Pandas
- Pickle

## 📌 Features

- Preprocessing: Tokenization, stopword removal, stemming.
- Vectorization using **TF-IDF**
- Binary classification using **Multinomial Naive Bayes**
- Easily extendable to web-based applications (Flask/Node.js backend)

## 🚀 How to Use

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/sentiment-analysis-ml.git
    cd sentiment-analysis-ml
    ```

2. Install required libraries:

    ```bash
    pip install -r requirements.txt  # (Create one if needed)
    ```

3. Run `predict.py` and enter your review:

    ```bash
    python predict.py
    ```

4. Example Output:

    ```
    Enter a customer review: The product was amazing!
    Predicted Sentiment: Positive
    ```

## 🔧 Future Improvements

- Add neutral sentiment detection
- Integrate with frontend via API
- Expand training dataset for better accuracy

## 📄 License

This project is open-source and available under the MIT License.
