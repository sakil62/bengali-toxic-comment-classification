# bengali-toxic-comment-classification
# Bengali Multi-Label Toxic Comment Classification using Hybrid Deep Learning

<div align="center">

### A Hybrid XLM-RoBERTa + BiLSTM + Multi-Head Attention Framework for Multi-Label Bengali Toxic Comment Detection

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep_Learning-EE4C2C?style=flat-square&logo=pytorch)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-FFD21E?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-success?style=flat-square)
![Research](https://img.shields.io/badge/Research-NLP-blueviolet?style=flat-square)

**Master of Computer Applications (MCA) Thesis Project**

University of Kalyani

</div>

---

## 📖 Overview

The rapid growth of social media has significantly increased the spread of toxic and abusive content, including hate speech, threats, insults, vulgar language, trolling, and religiously offensive comments. Automatic detection of such content is particularly challenging for Bengali due to limited annotated datasets and linguistic complexity.

This project proposes a **Hybrid Deep Learning Framework** that combines **XLM-RoBERTa**, **Bidirectional LSTM (BiLSTM)**, **Multi-Head Attention**, and **Focal Loss** for **multi-label Bengali toxic comment classification**. The framework predicts multiple toxicity categories simultaneously, making it suitable for intelligent content moderation systems.

---

## ✨ Key Features

- Multi-label Bengali Toxic Comment Classification
- XLM-RoBERTa Transformer Encoder
- Bidirectional LSTM (BiLSTM)
- Multi-Head Self-Attention
- Focal Loss for Class Imbalance
- Threshold Optimization
- Stratified Multi-Label Data Splitting
- End-to-End Deep Learning Pipeline
- Research-Oriented Evaluation

---

## 🎯 Toxicity Categories

| Label | Description |
|--------|-------------|
| Vulgar | Offensive or obscene language |
| Hate | Hate speech |
| Religious | Religion-based offensive content |
| Threat | Threatening language |
| Troll | Provocative or inflammatory comments |
| Insult | Personal abusive language |

---

## 🏗 Proposed Architecture

```
Input Bengali Comment
        │
        ▼
XLM-RoBERTa Tokenizer
        │
        ▼
XLM-RoBERTa Encoder
        │
        ▼
BiLSTM Layer
        │
        ▼
Multi-Head Attention
        │
        ▼
Dropout
        │
        ▼
Fully Connected Layer
        │
        ▼
Sigmoid Activation
        │
        ▼
Multi-Label Prediction
```

---

## ⚙️ Workflow

```
Dataset
   │
   ▼
Data Cleaning
   │
Unicode Normalization
   │
Tokenization
   │
Stratified Multi-Label Split
   │
Hybrid Deep Learning Model
   │
Threshold Optimization
   │
Evaluation
```

---

## 📊 Dataset

The dataset consists of Bengali social media comments annotated with six toxicity categories.

**Characteristics**

- Multi-label annotation
- Real-world Bengali comments
- Informal language
- Spelling variations
- Class imbalance
- Unicode normalization

---

## 🛠 Technologies

- Python
- PyTorch
- Hugging Face Transformers
- XLM-RoBERTa
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

## 📈 Experimental Results

| Metric | Score |
|---------|-------|
| Precision | **0.7657** |
| Recall | **0.7723** |
| Macro F1-Score | **0.7681** |
| Accuracy | **0.5945** |

### Model Comparison

| Model | Macro F1 |
|-------|----------|
| BanglaBERT + BiLSTM + CNN + Attention | 0.7462 |
| XLM-RoBERTa + CNN + BiLSTM + Attention | 0.7590 |
| **XLM-RoBERTa + BiLSTM + Attention + Focal Loss** | **0.7681** |

**Highlights**

- Best Validation Macro F1 Score: **0.7697**
- Stable convergence after approximately **50 epochs**
- Improved handling of class imbalance using **Focal Loss**
- Strong generalization with minimal overfitting

---

## 📂 Repository Structure

```
.
├── README.md
├── LICENSE
├── requirements.txt
├── best_model.pt
├── train.ipynb
├── thesis.pdf
├── dataset/
├── images/
└── results/
```

---

## 🚀 Installation

```bash
git clone https://github.com/sakil62/bengali-toxic-comment-classification.git

cd bengali-toxic-comment-classification

pip install -r requirements.txt
```

---

## 💻 Usage

Load the trained model

```python
best_model.pt
```

or run the notebook

```text
train.ipynb
```

to train and evaluate the model.

---

## 🔮 Future Work

- Explainable AI (XAI)
- Cross-Lingual Toxic Speech Detection
- Larger Bengali Datasets
- Lightweight Real-Time Deployment
- Graph Neural Networks
- Ensemble Learning

---

## 📄 Thesis

This repository contains the implementation developed as part of the MCA thesis project:

**Multi-Label Bengali Toxic Comment Classification using Hybrid Deep Learning Framework**

Department of Computer Science & Engineering  
University of Kalyani

---

## 👨‍💻 Authors

### Sakil Parvez

- 🎓 Master of Computer Applications (MCA)
- 🤖 Machine Learning | Deep Learning | NLP

**GitHub**

https://github.com/sakil62

**LinkedIn**

https://www.linkedin.com/in/sakil-parvez-24a151345/

---

## 📜 License

This project is licensed under the MIT License.

---

<div align="center">

⭐ If you found this repository useful, please consider giving it a star.

</div>
