# cosine_discounting

# Reproducing BERT Cosine Similarity Analysis

## Overview
This project contains code and resources to reproduce experiments on:
- The relationship between word frequency and BERT embeddings.
- Cosine similarity analysis for words in the WiC dataset.
- The effect of ℓ2 norm discounting on cosine similarity.

## Prerequisites
Before starting, ensure the following are installed:
- Python 3.8 or higher
- `pip` for Python package installation
- GPU (recommended for faster embedding generation)

## Install dependencies:
pip install torch transformers datasets nltk numpy matplotlib tqdm

## Download required NLTK resources:
python -c "import nltk; nltk.download('stopwords'); nltk.download('averaged_perceptron_tagger')"

Contact: Elham Akbari
Email: eakbari@gmu.edu
GitHub: https://github.com/akbarielham
