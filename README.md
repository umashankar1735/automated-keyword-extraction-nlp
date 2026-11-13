# Automated Keyword Extraction from Research Papers & Documents Using NLP

[![Python 3.8+](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

Academic NLP research project developed at **School of Computing, Amrita Vishwa Vidyapeetham, Amaravati** under the supervision of **Dr. Riyanka Manna**.

---

## 📌 Project Overview

This repository provides an automated pipeline for extracting high-salience keywords and technical phrases from unstructured academic research papers and scientific manuscripts. It evaluates both statistical (frequency-based), graph-based, and transformer-based embedding approaches to automatically generate candidate index terms.

---

## 🔬 Methods Implemented

1. **Statistical & Frequency Techniques**:
   - TF-IDF (Term Frequency - Inverse Document Frequency)
   - RAKE (Rapid Automatic Keyword Extraction)
   - YAKE! (Yet Another Keyword Extractor)

2. **Graph-Based Ranking**:
   - TextRank (PageRank applied to co-occurrence word networks)
   - SingleRank

3. **Transformer & Embedding-Based**:
   - **KeyBERT**: Leverages BERT embeddings and cosine similarity with maximal marginal relevance (MMR) for diverse, non-redundant phrase selection.

4. **Linguistic Pre-processing**:
   - Sentence tokenization, stopword filtering, POS tag patterns (noun-phrase chunking `(NN|NNS|JJ)+`), and lemmatization via NLTK & spaCy.

---

## 👥 Contributors

* **K. Sai Uma Shankar** (`AV.EN.U4CSE22119`)
* **P. Sashi Vardhan** (`AV.EN.U4CSE22132`)
* **R. Navaneeth** (`AV.EN.U4CSE22164`)
* **G. Ram Trilok** (`AV.EN.U4CSE22109`)
* **G. Sai Charan** (`AV.EN.U4CSE22157`)

**Project Supervisor**: **Dr. Riyanka Manna**, *Department of Computer Science and Engineering, Amrita Vishwa Vidyapeetham, Amaravati*.

---

## 📄 Deliverables in this Repository

- [`NLP_CODE.ipynb`](NLP_CODE.ipynb): Complete runnable notebook with text preprocessing, model implementations, and comparative precision/recall evaluations.
- [`NLP_FINAL_REPORT.pdf`](NLP_FINAL_REPORT.pdf): Formal academic project report and methodology breakdown.
- [`NLP.pptx`](NLP.pptx): Project defense presentation slides.

---

## 📄 License
MIT License.
