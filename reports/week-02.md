# Week 02 Progress Report

## Completed Work

This week the preprocessing pipeline was implemented. Text data was cleaned by converting reviews to lowercase, removing punctuation, and tokenizing words. Padding was applied to standardize sequence lengths.

A baseline machine learning model using TF-IDF vectorization and Logistic Regression was also trained and evaluated.

## Important Files and Commits

- Added preprocessing functions
- Added tokenizer and padding code
- Added baseline model implementation
- Added evaluation metrics

## Experiments and Results

The Logistic Regression baseline achieved reasonable performance on sentiment classification. Accuracy and F1-score were used for evaluation.

## Problems or Blockers

Some movie reviews are very long, which increases preprocessing complexity and memory usage.

## Plan for Next Week

- Build LSTM model
- Add embedding layer
- Train deep learning model
- Compare deep learning model with baseline
