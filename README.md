# 🛰️ PerProj — Wireless Signal Modulation Classification

## 📘 Introduction
**PerProj** is a machine learning and deep learning project focused on the **classification of wireless signal modulation types**.  
The goal is to build a model capable of identifying different **modulation schemes** (such as BPSK, QPSK, and 16-QAM) from radio signals affected by various **Signal-to-Noise Ratio (SNR)** conditions.

This project uses the **RadioML 2018.01A** dataset and explores different models, including **Convolutional Neural Networks (CNN)** and **Bidirectional LSTM**, for accurate signal classification.

---

## 📂 Dataset
**Dataset used:** [RadioML 2018.01A](https://www.kaggle.com/datasets/pinxau1000/radioml2018)

The dataset contains:
- Various modulation types (ASK, PSK, QAM, AM, FM)
- Signals under different SNR levels (from +30 dB to -20 dB)
- I/Q (In-phase and Quadrature) signal components for each sample

### Example of selected modulation classes
```python
selected_modulation_classes = [
    '4ASK', 'BPSK', 'QPSK', '16PSK', 
    '16QAM', 'FM', '32APSK', '64QAM', 
    '128QAM', 'AM-SSB-WC'
]
