# 💬 Sentiment Analysis using SVM and TF-IDF

This project demonstrates how to perform sentiment classification on text data using **Support Vector Machine (SVM)** and **TF-IDF vectorization**. The model predicts whether a text expresses **positive** or **negative** sentiment based on learned patterns from a small sample movie review dataset.

---

## 🚀 Features

- Converts raw text to numeric features using **TF-IDF**
- Trains an SVM classifier with a **linear kernel** (ideal for text classification)
- Evaluates performance using a **classification report**
- Extracts and plots the most influential **positive and negative features**
- Visualizes top coefficients contributing to sentiment prediction

---

## 📝 Dataset

A synthetic list of short movie reviews with manually labeled sentiments:

- `1` = Positive sentiment
- `0` = Negative sentiment

---

## 📊 Example Output

```text
              precision    recall  f1-score   support

    Negative       1.00      0.75      0.86         4
    Positive       0.80      1.00      0.89         4

    accuracy                           0.88         8
   macro avg       0.90      0.88      0.88         8
weighted avg       0.90      0.88      0.88         8
```
And a bar chart visualizing top positive and negative words based on their SVM coefficients.

---
## 🛠️ How to Run

1. Clone the repository:
```
git clone https://github.com/NoorNick/Text-Classification.git
cd Text-Classification

```
2. Install the required packages:
```
pip install -r requirements.txt
```
3. Launch the notebook:
```
jupyter notebook
```
Then open text_classification.ipynb and run all cells.

---
## 📌 Techniques Used
- TF-IDF Vectorization for feature extraction

- Support Vector Machine (SVC) for classification

- Train-test split with sklearn

- Interpretability through feature coefficient analysis

---
Train smarter, classify better. 🧠📊







