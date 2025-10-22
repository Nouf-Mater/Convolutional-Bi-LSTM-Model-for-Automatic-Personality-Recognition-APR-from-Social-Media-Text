## 🌟 Project Overview

This repository contains the code and resources for a **Deep Learning / Natural Language Processing (NLP)** project focused on **Automatic Personality Recognition (APR)**. The project's goal was to build a robust model to infer the **Big Five personality traits** (Openness, Conscientiousness, Extraversion, Agreeableness, and Neuroticism) directly from social media users' text posts.

This work was published as a peer-reviewed research paper (citation below).

---

## 💡 Key Contributions & Data Science Skills

* **Problem Solved:** Developed an end-to-end multi-label classification system to model complex psychological traits from noisy, unstructured social media data.
* **Novel Architecture (APR_ConvLSTM):** Implemented a hybrid deep learning model combining a **Convolutional Neural Network (CNN)** for local feature extraction (n-gram patterns) with a **Bidirectional Long Short-Term Memory (Bi-LSTM)** network for capturing long-range contextual dependencies.
* **Data Handling:** Managed and pre-processed large volumes of real-world text data, including tokenization, sequence padding, and the use of pre-trained **Word Embeddings** (e.g., GloVe) for dense data representation. A novel labeled dataset (X-Big5) was also utilized.
* **Performance:** Achieved **competitive, state-of-the-art results** (e.g., up to 88.60% F1-score for Openness) compared to traditional Machine Learning and prior Deep Learning approaches, demonstrating model efficiency and accuracy.
* **Efficiency:** Created a unified model to predict **all five traits simultaneously**, significantly streamlining the deployment and inference process compared to running five separate models.

---

## 🛠️ Technology Stack

* **Programming Language:** Python
* **Deep Learning Framework:** TensorFlow / Keras (or PyTorch - *Choose the one you used*)
* **Core Libraries:** Pandas, NumPy, Scikit-learn
* **NLP Tools:** Word Embeddings (GloVe/Word2Vec), Tokenization utilities
* **Code is available in:** `model_training.ipynb` (or `main.py`)

---

## 📄 Publication Details (The Portfolio Link)

The full technical details, methodology, and results are available in the following publication:

**Title:** Convolutional Bi-LSTM for Automatic Personality Recognition From Social Media Texts
**Authors:** [List Authors]
**Journal:** IEEE Access
**DOI:** [Insert DOI from your paper, e.g., 10.1109/ACCESS.2025.3558714]

**Link to Paper:** [Insert the journal's public URL for your paper here]
