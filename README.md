# NLP Probability Distribution and Entropy Analysis

This Python script analyzes text data by computing probability distributions, entropy, and KL divergence between datasets. It also calculates the entropy rate of a message given a probability distribution.

## Table of Contents

- [Introduction](#Introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)

## Introduction

This script aims to provide insights into text data using Natural Language Processing (NLP) techniques. It performs the following tasks:

- Tokenizes datasets
- Calculates probability distributions
- Computes entropy of probability distributions
- Measures KL divergence between datasets
- Determines entropy rate of a message given a probability distribution

The script utilizes the SST (Stanford Sentiment Treebank) and QNLI (Question Natural Language Inference) datasets obtained from the [GLUE Benchmark](https://gluebenchmark.com/tasks).
 
## Dependencies

- Python 3.12
- pandas
- NLTK (Natural Language Toolkit)

Install NLTK using the following command:
    ``` pip install nltk ```

## Usage

1. Clone the repository:
    ``` git clone https://github.com/sohamvsonar/ProbabilityDistribution.git ```

2. Install the dependencies:

3. Run the script:
    ``` python entropy_analysis.py ```

## Functions

- probability_distribution(token_list): Calculates the probability distribution of a token list.
- find_entropy(probability_distribution): Computes the entropy of a probability distribution.
- find_kl_divergence(pd_1, pd_2): Computes the KL divergence between two probability distributions.
- find_entropy_rate(message, probability_distribution): Determines the entropy rate of a message given a probability distribution.