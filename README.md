# Wikipedia Movie Plot ML Project By Almohtadey

## 1. Introduction
- **Objective**: Predict movie genres and generate non-spoiler plot summaries using Wikipedia movie plot data.
- **Dataset**: Scraped from Wikipedia, includes 34,000+ movies with metadata and plot descriptions.

## 2. Data Exploration
- Load and inspect the dataset
- Analyze null values, column types
- Visualize distribution of genres, origins, release years
- Check text length distribution of plots

## 3. Data Preparation
- Handle missing values (drop, fill, etc.)
- Clean or simplify genre labels (e.g., remove 'unknown')
- Text preprocessing (lowercasing, stopword removal, tokenization)
- Vectorize plot descriptions (TF-IDF )
- Encode genres

## 4. Modeling
- Baseline model (Logistic Regression, )
- # Wikipedia Movie Plot ML Project

## 1. Introduction
- **Objective**: Predict movie genres and generate non-spoiler plot summaries using Wikipedia movie plot data.
- **Dataset**: Scraped from Wikipedia, includes 34,000+ movies with metadata and plot descriptions.

## 2. Data Exploration
- Load and inspect the dataset
- Analyze null values, column types
- Visualize distribution of genres, origins, release years
- Check text length distribution of plots

## 3. Data Preparation
- Handle missing values (drop, fill, etc.)
- Clean or simplify genre labels (e.g., remove 'unknown')
- Text preprocessing (lowercasing, stopword removal, tokenization)
- Vectorize plot descriptions (TF-IDF or embeddings)
- Encode genres

## 4. Modeling
- Baseline model (Logistic Regression)
- Intermediate model (Random Forest)
- Adanced Model (XGBoost)
-  Transformer-based model (	facebook/bart-large-cnn )
- Model Tuning & Acceptenace Criteria

## 5. Evaluation
- Accuracy /F1 / Precision / Recall per genre
- Model comparison

## 6. LLM-Based Non-Spoiler Summarization
- Use Hugging Face models to generate 5–10 summaries
- Avoid spoilers and compare with original plot using Blockers

## 7. Conclusions
- Recap of results
- Challenges faced
- What could be done next (multi-label, richer features, etc.)


