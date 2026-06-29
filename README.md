# 🤖 Part-of-Speech (POS) Tagging using Hidden Markov Models (HMM)

<p align="center">

<img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

<img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-8A2BE2?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Hidden-Markov%20Model-success?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Viterbi-Algorithm-orange?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge"/>

<img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge"/>

</p>



## 📖 Overview

This project presents a complete implementation of a **Part-of-Speech (POS) Tagger** using the **Hidden Markov Model (HMM)** and the **Viterbi Algorithm**. The model is trained on the **Brown Corpus** provided by the Natural Language Toolkit (NLTK) and predicts the most probable grammatical tag for every word in a sentence.

Unlike modern deep learning approaches, this implementation focuses on the statistical foundations of sequence modeling, making it an excellent educational and portfolio project for understanding probabilistic Natural Language Processing.



## ✨ Key Features

* 📚 Brown Corpus preprocessing using NLTK
* 📝 Corpus statistics and vocabulary analysis
* 📊 POS tag frequency distribution
* 🧠 Hidden Markov Model implementation from scratch
* 🔄 Transition probability estimation
* 🔤 Emission probability estimation
* ⚡ Viterbi Algorithm for optimal sequence decoding
* 🏷️ Part-of-Speech tagging for unseen sentences
* 📈 Model evaluation using Accuracy, Precision, Recall, and F1-score
* 📉 Confusion Matrix visualization
* 🌍 Out-of-Vocabulary (OOV) word analysis
* 📑 Comprehensive project report



## 🧠 What is Part-of-Speech (POS) Tagging?

Part-of-Speech (POS) Tagging is a fundamental Natural Language Processing (NLP) task where each word in a sentence is assigned its grammatical category, such as:

| Word  | POS Tag |
| ----- | ------- |
| The   | DET     |
| quick | ADJ     |
| brown | ADJ     |
| fox   | NOUN    |
| jumps | VERB    |
| over  | ADP     |
| the   | DET     |
| lazy  | ADJ     |
| dog   | NOUN    |

This process enables computers to understand sentence structure and forms the basis for applications such as machine translation, information retrieval, sentiment analysis, speech recognition, and question answering.

## 🌟 Project Highlights

- **Trained on** 10,000 manually tagged sentences from the Brown Corpus
- **Core Implementation**: Hidden Markov Model + Viterbi Decoding
- **Advanced Techniques**: Laplace Smoothing, Dynamic Programming
- **Comprehensive Analysis**: Corpus statistics, OOV handling, Model Evaluation
- **Educational Focus**: Classical Probabilistic NLP vs Modern Neural Approaches


## 📈 Dataset & Statistics

| Metric                    | Value              | Description |
|--------------------------|--------------------|-----------|
| Sentences                | **10,000**         | Training data |
| Total Tokens             | **219,770**        | Words processed |
| Vocabulary Size          | **21,248**         | Unique words |
| Unique POS Tags          | **12**             | Universal Tagset |

**POS Tags Used**: `NOUN, VERB, ADJ, ADV, DET, PRON, ADP, ., CONJ, NUM, PRT, X`

---

## 🛠️ Technology Stack

**Core**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python) 
![NLTK](https://img.shields.io/badge/NLTK-4B8BBE?style=flat)

**Data & Visualization**  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat) 
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat) 
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat) 
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat)

**Evaluation**  
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat)

---

## 🎯 Project Objectives

* Build a statistical POS Tagger using Hidden Markov Models.
* Learn transition and emission probabilities from annotated text.
* Implement the Viterbi Algorithm for sequence prediction.
* Evaluate model performance using standard classification metrics.
* Analyze the impact of unseen (Out-of-Vocabulary) words.
* Demonstrate the complete NLP pipeline from preprocessing to evaluation.



## 🔄 Project Workflow

```text
Brown Corpus
      │
      ▼
Data Preprocessing
      │
      ▼
Corpus Analysis
      │
      ▼
Vocabulary Statistics
      │
      ▼
Transition Probability
      │
      ▼
Emission Probability
      │
      ▼
Hidden Markov Model
      │
      ▼
Viterbi Algorithm
      │
      ▼
POS Prediction
      │
      ▼
Model Evaluation
      │
      ▼
Confusion Matrix
      │
      ▼
OOV Analysis
```


## Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/POS-Tagger-HMM-Viterbi.git
cd POS-Tagger-HMM-Viterbi

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook notebook/POS_Tagger_HMM.ipynb

