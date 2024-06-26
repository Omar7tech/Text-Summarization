# 📄 Text Summarization Project

This repository demonstrates the process of automatic text summarization using both traditional methods and modern NLP models. The steps include text cleaning, word frequency analysis, and the implementation of summarization algorithms. Additionally, we compare paraphrased summaries generated by different transformer models.

---

## 📑 Table of Contents

1. [📘 Introduction](#-introduction)
2. [📈 Importance of Text Summarization](#-importance-of-text-summarization)
3. [🔍 Steps in Text Summarization](#-steps-in-text-summarization)
4. [⚙️ Setup and Installation](#-setup-and-installation)
5. [💻 Code Implementation](#-code-implementation)
6. [🔄 Model Comparison](#-model-comparison)
7. [📊 Final Results](#-final-results)
8. [📊 Statistics](#-statistics)

---

## 📘 Introduction

**Text summarization** is the process of distilling the most important information from a source text. It aims to provide a concise version of the content, retaining key points and main ideas.

## 📈 Importance of Text Summarization

The importance of automatic text summarization lies in several key benefits:
1. **⏱️ Reduced Reading Time:** Summaries significantly cut down the time needed to read and understand large documents.
2. **📂 Easier Document Selection:** Summaries simplify the process of choosing relevant documents during research.
3. **📚 Improved Indexing Effectiveness:** Summaries enhance the efficiency of indexing systems.
4. **⚖️ Reduced Bias:** Automated summarization is less prone to bias compared to human summarizers.
5. **📝 Personalized Information:** Customized summaries are valuable in question-answering systems as they provide tailored information.
6. **🚀 Increased Processing Capacity:** Automated summarization allows handling a larger volume of text documents.

## 🔍 Steps in Text Summarization

1. **Text Cleaning**
   - Word Tokenization
   - Sentence Tokenization
2. **Word-Frequency Table**
3. **Summarization**

## ⚙️ Setup and Installation

To set up the environment, follow these steps:

```sh
# Install spaCy
pip install -U spacy

# Download spaCy language model
python -m spacy download en_core_web_sm
