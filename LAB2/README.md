# Lab 2 — Sentiment Classification on a Real Dataset

This lab extends the toy example from Lab 1 by training a sentiment classifier on a real-world dataset. The notebook is dataset‑agnostic: users can upload any CSV file containing a text column and a label column.

## Features
- User‑uploaded dataset (CSV)
- Dynamic column selection for text + labels
- Train/test split
- TF‑IDF vectorization with stopwords and feature limits
- Logistic Regression classifier
- Accuracy + classification report
- Interactive testing menu for custom sentences

## How to Run
1. Open the notebook in Google Colab.
2. Upload your CSV dataset when prompted.
3. Enter the names of the text and label columns.
4. Run all cells to train and evaluate the model.
5. Use the interactive menu to test custom sentences.

## Dataset Requirements
Your CSV must contain:
- One column with text (e.g., review, tweet, comment)
- One column with sentiment labels (e.g., positive/negative)

## Dependencies
See `requirements.txt`.
