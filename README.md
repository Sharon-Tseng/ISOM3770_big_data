# ISOM 3770: Big Data Analytics Projects

This repository contains coursework assignments for ISOM 3770 - Big Data Analytics at HKUST, showcasing implementations of distributed computing algorithms using Apache Spark.

## 📚 Projects Overview

### Assignment 2: PageRank Algorithm
**File:** [assignment2_pagerank_Tseng,YungYi.ipynb](assignment2_pagerank_Tseng,YungYi.ipynb)

Implementation of Google's PageRank algorithm using PySpark. This project demonstrates the use of iterative algorithms in a distributed computing environment to rank web pages based on their link structure.

**Key Features:**
- Spark RDD operations for distributed graph processing
- Iterative computation of page rankings
- Link analysis on sample network data

**Technologies:**
- Apache Spark 3.4.0
- PySpark
- Python

### Assignment 3: Sentiment Analysis
**File:** [assignment3_sentiment.ipynb](assignment3_sentiment.ipynb)

A machine learning project that builds a sentiment classifier for Amazon product reviews using Spark ML. This project applies natural language processing and classification techniques to predict customer sentiment from review text.

**Key Features:**
- Text processing and tokenization with Spark ML
- Feature extraction using CountVectorizer
- Binary classification for sentiment prediction
- Model evaluation and performance metrics

**Technologies:**
- Apache Spark 3.4.0
- Spark ML (Machine Learning Library)
- Logistic Regression & Random Forest classifiers
- Python

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Java 11
- Apache Spark 3.4.0
- Jupyter Notebook or Google Colab

### Running on Google Colab
Both notebooks are configured to run on Google Colab with setup cells included:

1. Click the "Open in Colab" badge at the top of each notebook
2. Run the first cell to install dependencies (Java, Spark, findspark)
3. Follow the instructions in each notebook

### Running Locally
```bash
# Install required packages
pip install pyspark findspark jupyter

# Set environment variables
export JAVA_HOME=/path/to/java-11
export SPARK_HOME=/path/to/spark-3.4.0

# Launch Jupyter Notebook
jupyter notebook
```

## 📊 Datasets

- **Assignment 2:** Sample network graph with page links
- **Assignment 3:** Amazon product review dataset (downloaded from provided link)

## 📝 License

This repository contains academic coursework and is intended for educational purposes in the Hong Kong University of Science and Technology (HKUST).

## 🔗 Links

- [Open Assignment 2 in Colab](https://colab.research.google.com/github/Sharon-Tseng/ISOM3770_Big_Data/blob/main/assignment2_pagerank_Tseng%2CYungYi.ipynb)
- [Open Assignment 3 in Colab](https://colab.research.google.com/github/Sharon-Tseng/ISOM3770_big_data/blob/main/assignment3_sentiment.ipynb)