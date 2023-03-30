# NLP Pipeline for Fake News Prediction

- Built an NLP pipeline for fake news prediction using TF-IDF for text embedding and SVM for classification.
- Achieved 99.4% accuracy for SVMs on a preprocessed dataset of news articles.
- Incorporated text summarization using Hugging Face's transformers library to provide concise summaries of news articles.

## Objective

The objective of this project was to build an NLP pipeline for fake news prediction using TF-IDF for text embedding and SVM for classification. The pipeline was also designed to include text summarization using Hugging Face's transformers library.

## Methodology

The following steps were taken to achieve the project's objective:

1. Dataset Collection: A dataset of news articles, containing both real and fake news, was collected from various sources. The dataset was preprocessed and cleaned to remove any unnecessary data.

2. Text Embedding: The text data was converted into numerical features using the Term Frequency-Inverse Document Frequency (TF-IDF) technique. This helped in creating a feature matrix that represents the text data.

3. Model Training: SVMs were used for classification, as they have been proven to be highly accurate for text classification tasks. The model was trained on the preprocessed dataset to classify news articles as either real or fake.

4. Evaluation: The accuracy of the SVM model was evaluated using cross-validation techniques. The model achieved an accuracy of 99.4%.

5. Text Summarization: To provide a summary of news articles, Hugging Face's transformers library was used. The library provides state-of-the-art pre-trained models for natural language processing, including summarization.

## Installation

1. Clone the repository

```bash
git clone https://github.com/kulsumkamal/fake-news-detection.git
```

2. Install the required packages

```bash
pip install -r requirements.txt
```

## Results

The NLP pipeline built for fake news prediction achieved an accuracy of 99.4% for SVMs. Text summarization using Hugging Face provided a concise summary of the news articles, making it easier to identify fake news.

## Conclusion

The project demonstrates the effectiveness of using TF-IDF and SVMs for fake news prediction. The pipeline can be extended to include other classification algorithms and can be applied to other text classification tasks. The inclusion of text summarization using Hugging Face makes it an all-in-one solution for news analysis.
