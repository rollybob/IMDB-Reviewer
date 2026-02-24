## Sentiment Analysis with Fine-Tuned DistilBERT

Fine-tuning a pre-trained transformer model for movie review sentiment classification.

## Results
- **Accuracy: 85.5%**
- Base model: distilbert-base-uncased
- Dataset: IMDB (25,000 movie reviews)
- Training: 10 epochs using HuggingFace Trainer API

## Steps Taken
1. Loaded pre-trained DistilBERT model from HuggingFace
2. Prepared IMDB dataset with proper tokenization
3. Fine-tuned using transfer learning on sentiment classification task
4. Evaluated on held-out test set

## Technologies
- Python
- HuggingFace Transformers
- PyTorch
- Google Colab (free GPU)

## Key Learnings
- Transfer learning dramatically reduces training time and data requirements
- Pre-trained language models adapt quickly to domain-specific tasks
- HuggingFace Transformers library makes state-of-the-art NLP accessible

## How to Run
Open the notebook in Google Colab and run all cells.
