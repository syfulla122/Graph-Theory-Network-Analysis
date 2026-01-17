# Neural Text Processing Engine (NLP)

### 📋 Overview
This project demonstrates **custom Deep Learning implementation** for Natural Language Processing tasks. Instead of relying solely on pre-built APIs, this repository contains models built from scratch using **TensorFlow/Keras** to understand the mathematical foundations of text generation and sentiment analysis.

### 🛠️ Key Modules
1.  **Next-Word Prediction (Generative AI):**
    * **Architecture:** LSTM (Long Short-Term Memory) network.
    * **Process:** Tokenization $\rightarrow$ N-Gram Sequences $\rightarrow$ Embedding Layer $\rightarrow$ LSTM $\rightarrow$ Dense Output.
    * **Use Case:** Autocomplete systems and chat agents.

2.  **Yelp Sentiment Classifier:**
    * **Architecture:** Embedding + LSTM.
    * **Process:** Handles variable-length text via `pad_sequences` to classify customer reviews with high precision.

### 💻 Tech Stack
* **Framework:** TensorFlow, Keras
* **Preprocessing:** NLTK, Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn

### 📊 Results
* Successfully trained a model to predict sequential text data with minimized categorical cross-entropy loss.
* Implemented custom text cleaning pipelines (Stopword removal, RegEx filtering) to ensure clean input data.

### 🚀 How to Run
```bash
pip install tensorflow pandas numpy nltk
jupyter notebook "Next_Word_Prediction_LSTM.ipynb"# Graph-Theory-Network-Analysis
