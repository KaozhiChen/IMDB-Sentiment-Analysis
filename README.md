# Sentiment Analysis on IMDB Movie Reviews

## Project Overview
This project compares the performance of traditional machine learning (Naive Bayes) and modern NLP techniques (Hugging Face's DistilBERT) for sentiment analysis on the IMDB dataset.

## Methods
1. **Data Preprocessing**:
   - Extracted text and labels from the dataset.
   - Vectorized text using TF-IDF.
   - Truncated long texts to fit model input requirements.

2. **Modeling**:
   - Implemented Naive Bayes with sklearn.
   - Utilized Hugging Face's pipeline for modern NLP sentiment analysis.

3. **Visualization**:
   - Generated word clouds to analyze sentiment distribution.

## Results
| Model         | Test Accuracy |
|---------------|---------------|
| Naive Bayes   | 85%           |
| DistilBERT    | 82%           |

## Conclusion
Naive Bayes outperformed DistilBERT due to the dataset size and the impact of text truncation on modern NLP models. Hugging Face models are better suited for complex semantics with fine-tuning and larger datasets.
