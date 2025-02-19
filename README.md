# Fake News Detection

**Fake News Detection** is a machine learning project aimed at detecting fake news  using a **TfidfVectorizer** and a **Support Vector Classifier (SVC)** pipeline. The model analyzes news articles and classifies them as either **real** or **fake** based on the textual content.

---

## Features
- **TfidfVectorizer**: Converts raw text data into numerical vectors by considering the importance of each word in the corpus.
- **SVC**: A Support Vector Classifier is used for classification, leveraging the vectors generated by the TfidfVectorizer to distinguish between fake and real news.
- **Pipeline**: Combines the TfidfVectorizer and SVC into a single unified workflow for efficient data processing and model training.

---

## Tech Stack
- **Machine Learning**: Python, Scikit-learn
- **Text Vectorization**: TfidfVectorizer
- **Model**: Support Vector Classifier (SVC)
- **Libraries**: Pandas,  Scikit-learn

---

## How It Works

1. **Data Preprocessing**: The raw news text data is processed using **TfidfVectorizer**, which converts the text into numerical features based on word importance.
2. **Model Training**: The processed features are used to train an **SVC** classifier. The model learns patterns in the text that distinguish between real and fake news.
3. **Prediction**: The trained model can then predict whether a new piece of text is real or fake based on the features learned during training.

---
