# Emotion Detection Using Bidirectional LSTM

## 📌 Overview
This project implements a Bidirectional Long Short-Term Memory (BiLSTM) network for multi-class emotion classification (13 emotion categories). The model achieves 92% classification accuracy.

---

## 🎯 Problem Statement
Emotion detection from text plays a crucial role in sentiment analysis, human-computer interaction, and mental health monitoring.

---

## 📊 Dataset
- 13 emotion classes
- Preprocessed with tokenization and padding
- Train/Test split: 80/20

---

## 🏗 Model Architecture

Embedding Layer  
↓  
Bidirectional LSTM  
↓  
Dropout  
↓  
Dense Layer (Softmax)

---

## 📈 Results

- Accuracy: 92%
- Cross-entropy loss optimized with Adam
- Early stopping applied

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
python src/train.py
