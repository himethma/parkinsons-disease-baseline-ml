# parkinsons-disease-baseline-ml
Baseline Logistic Regression and Random Forest models for Parkinson's Disease classification using the UCI voice dataset.

# Parkinson's Disease Baseline Machine Learning Models

This repository contains the baseline implementation developed for Phase 2 of my Machine Learning coursework.

## Models
- Logistic Regression
- Random Forest

Both models were also tuned using RandomizedSearchCV.

## Dataset
UCI Parkinson's Disease Dataset:
https://archive.ics.uci.edu/dataset/174/parkinsons

The dataset contains 195 voice recordings and 22 predictive features.

## Main Results

| Model | Accuracy | Precision | Recall | F1-score |
|---|---:|---:|---:|---:|
| Untuned Logistic Regression | 92.31% | 93.33% | 96.55% | 94.92% |
| Tuned Logistic Regression | 79.49% | 92.00% | 79.31% | 85.19% |
| Untuned Random Forest | 92.31% | 93.33% | 96.55% | 94.92% |
| Tuned Random Forest | 92.31% | 93.33% | 96.55% | 94.92% |

## Running the Notebook
1. Download the UCI Parkinson's dataset.
2. Open `parkinsons_baseline_models.ipynb` in Google Colab.
3. Run the cells from top to bottom.
4. Upload `parkinsons.data` when requested.

## Limitation
The experiment uses a recording-level 80:20 stratified split. Since multiple recordings belong to the same participants, the results should not be treated as a participant-independent clinical evaluation.
