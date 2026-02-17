# Natural Language Processing (NLP) – Text Classification Pipeline

## Project Overview
This project focuses on utilizing Natural Language Processing (NLP) methods to automate the classification of technical reports.  
The primary goal is to distinguish between texts related to **geology** (e.g., ore deposits, geophysical surveys) and **space exploration** reports (e.g., Mars missions, space probes).

## Key Features
* **End-to-End Pipeline**: Automated data processing workflow using the `scikit-learn Pipeline`.
* **Text Preprocessing**: Implementation of custom cleaning functions, including stop-word removal, punctuation stripping, and case normalization.
* **Deep Learning Architecture**: Binary classifier built with Keras/TensorFlow using `Embedding`, `Flatten`, and `Dense` layers.
* **Tokenization & Padding**: Transformation of raw text into fixed-length numerical sequences for neural network compatibility.

## Tech Stack
* **Language**: Python 
* **Libraries**: TensorFlow/Keras, Scikit-learn, NumPy, Re (Regular Expressions).

---

## 💻 How to Run This Project
1. Open the `NLP_Czop_Natalia.ipynb` file in **Google Colab** or a local **Jupyter Notebook** environment.
2. Install the required dependencies:  
   ```pip install tensorflow scikit-learn numpy
