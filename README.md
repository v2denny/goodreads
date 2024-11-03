# TAAC Project - FCUP

This project was developed as part of the TAAC course at the Faculty of Sciences, University of Porto (FCUP).

## Project Members
- **Daniel Dias**
- **Lucas Santiago**
- **Rafael Conceição**

## Overview
The goal of this project is to predict book ratings and genres based on user review texts using the Goodreads dataset.

## Tools & Libraries
We utilized the following tools and libraries to achieve our objectives:
- **Optuna**: For hyperparameter tuning
- **DistilBERT (uncased)**: A pre-trained language model used in fine-tuning tasks
- **Ray**: To enable distributed data processing
- **Modin**: For efficient handling of large datasets
- **SHAP**: For identifying the most important words impacting model predictions

## Project Structure
The project is organized into the following steps, each documented in corresponding Jupyter notebooks:

- **step0.ipynb**: Merges the reviews and genres datasets.
- **step1.ipynb**: Preprocesses the dataset and selects 15k entries per genre.
- **step2.ipynb**: Fine-tunes the DistilBERT (uncased) LLM using Optuna for optimal hyperparameters.
- **step3.ipynb**: Classifies genres and identifies the most important words for each classification.
- **step4.ipynb**: Determines the key words influencing the model's rating predictions using SHAP.

## Dataset
This project uses the Goodreads dataset, which includes information about books, reviews, genres, and ratings.

---

This project leverages advanced NLP techniques and hyperparameter tuning to analyze and predict book ratings and genres, providing insights into the relationships between user reviews and genre classifications.
