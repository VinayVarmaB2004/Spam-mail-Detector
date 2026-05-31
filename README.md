# Spam Email Classification Web App

An NLP-powered web application that classifies emails as Spam or Ham (Not Spam) using Machine Learning techniques. The system leverages TF-IDF vectorization and a Naïve Bayes classifier to accurately detect unwanted emails in real time.

## Live Demo

🔗 https://spam-mail-detector-cwnlynh5knfvuuar7fuswv.streamlit.app/

## Features

- Real-time spam email prediction
- NLP-based text preprocessing pipeline
- TF-IDF feature extraction
- Naïve Bayes classification
- Interactive Streamlit web interface
- Instant prediction results

## Dataset

- 5,000+ email records
- Spam and Ham email categories
- Used for training and evaluating the classification model

## Tech Stack

- Python
- Natural Language Processing (NLP)
- Scikit-learn
- TF-IDF Vectorization
- Naïve Bayes
- Streamlit

## Machine Learning Pipeline

### Text Preprocessing

The email text undergoes:

- Tokenization
- Lowercasing
- Stop-word Removal
- Stemming
- Lemmatization

### Feature Engineering

- TF-IDF Vectorization converts textual data into numerical feature vectors.

### Model Training

- Multinomial Naïve Bayes classifier trained on processed email data.

### Prediction

- Incoming email text is transformed using the trained TF-IDF model.
- The classifier predicts whether the email is Spam or Ham.

## Model Performance

| Metric | Score |
|----------|----------|
| Accuracy | 98% |
| Precision | 96% |
| Recall | 97% |
| F1-Score | 97% |

## Workflow

1. User enters email text.
2. Text preprocessing is applied.
3. TF-IDF vectorization converts text into features.
4. Naïve Bayes model performs classification.
5. Prediction is displayed instantly.

## Applications

- Email filtering systems
- Enterprise communication platforms
- Cybersecurity solutions
- Personal email management
- Spam detection services

## Project Highlights

✅ NLP-Based Classification

✅ TF-IDF Feature Engineering

✅ Naïve Bayes Machine Learning Model

✅ 98% Prediction Accuracy

✅ Streamlit Web Application

✅ Real-Time Email Classification

## Future Enhancements

- Deep Learning Models (LSTM/BERT)
- Multi-language Spam Detection
- Email Attachment Analysis
- Explainable AI Predictions
- API Deployment

- GitHub: https://github.com/VinayVarmaB2004
- LinkedIn: https://www.linkedin.com/in/vinayvarmab04/
