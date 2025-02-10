# Fake News Detection with DistillBERT

This project applies machine learning and natural language processing (NLP) techniques to detect fake news using the **WELFake dataset**. The dataset consists of 72,134 news articles, which I downsampled to 20,000 articles to optimize for computational constraints.

## Key Highlights:
- **Data Preprocessing**:
  - Removed missing values
  - Tokenized text
  - Removed URLs and stop words
  - Applied stemming to standardize text data

- **Model Selection**: 
  - Used **DistillBERT**, a lightweight version of BERT, for text classification

- **Dataset Split**: 
  - 64% training, 16% validation, and 20% test sets

- **Results**: 
  - Achieved **98.19% test accuracy** after training for 3 epochs

## Conclusion:
This project demonstrates proficiency in handling large datasets, effective data preprocessing, and leveraging advanced NLP models like DistillBERT for real-world applications such as fake news detection.

## Technologies Used:
- Python
- DistillBERT
- Pandas
- Numpy
- Hugging Face Transformers
