# ITNPAI1 Assignment – Comparative Evaluation of BERT and RoBERTa for Sentiment Classification

## Overview
This notebook compares BERT and RoBERTa on two sentiment classification datasets:
- IMDB movie reviews
- TripAdvisor hotel reviews

The task is binary sentiment classification.

## Models
- `bert-base-uncased`
- `roberta-base`

## Datasets
- IMDB dataset loaded from Hugging Face
- TripAdvisor Hotel Reviews dataset downloaded from Kaggle
  Datasets used:

1. IMDB Movie Review Dataset
https://huggingface.co/datasets/stanfordnlp/imdb

2. TripAdvisor Hotel Reviews
https://www.kaggle.com/datasets/andrewmvd/trip-advisor-hotel-reviews

## How to run
1. Install the required libraries.
2. Download/load the datasets.
3. Preprocess the datasets into binary sentiment labels.
4. Convert data into Hugging Face Dataset format.
5. Run training/evaluation cells for each experiment.
6. View final metrics and confusion matrices.

## Reproducibility
- Random seed: 42
- Same train/validation/test logic used across experiments
- Same evaluation metrics used for all models

## Notes
This notebook was cleaned from the development version for submission.
