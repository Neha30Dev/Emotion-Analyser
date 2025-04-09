# Emotion Analyser Chatbot

A Natural Language Processing (NLP) based chatbot that analyzes the emotional tone of text using a Logistic Regression model. The chatbot is deployed with an interactive web interface using **Gradio**.

---

## Project Overview

This project classifies user input text into one of the following six emotion categories:

- Sadness  
- Joy  
- Love  
- Anger  
- Fear  
- Surprise  

It leverages **TF-IDF** vectorization for feature extraction and **Logistic Regression** for classification.

---

## Dataset

The dataset used in this project includes three CSV files:

- `training.csv`
- `validation.csv`
- `test.csv`

Each file contains:

- `text` – The input sentence  
- `label` – An integer from 0 to 5 representing the emotion class

| Label | Emotion   |
|-------|-----------|
| 0     | Sadness   |
| 1     | Joy       |
| 2     | Love      |
| 3     | Anger     |
| 4     | Fear      |
| 5     | Surprise  |

---

## 🛠 Setup Instructions

Follow these steps to run the project on your local machine.

### Prerequisites

Make sure Python is installed on your system. Recommended version: Python 3.8 or above.

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/emotion-analyser-chatbot.git
cd emotion-analyser-chatbot
```

### 2. Install requirements

```bash
pip install pandas scikit-learn gradio joblib
```
