# Twitter Airline Sentiment Analysis with LSTM & Attention Mechanism

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.8%2B-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A comprehensive sentiment analysis project using advanced deep learning techniques to classify Twitter US Airline sentiment into positive, neutral, and negative categories.

## 📋 Project Overview

This project implements an advanced sentiment analysis system using:
- **Bidirectional LSTM/GRU** with **Attention Mechanism**
- Comparison with a **baseline neural network model**
- Handling of **imbalanced multi-class classification**
- **Attention visualization** for model interpretability

## 🏗️ Project Structure

Twitter-Sentiment-Analysis-LSTM-Attention/
├── data/ # Dataset directory
├── notebooks/ # Jupyter notebooks
├── models/ # Saved models
├── results/ # Output figures and metrics
├── requirements.txt # Python dependencies
|── README.md # This file
|__ environment.yml


## 📊 Dataset

**Twitter US Airline Sentiment Dataset** from Kaggle:
- **3 classes**: Negative (9,178), Neutral (3,099), Positive (2,363)
- Real-world, messy Twitter data
- Imbalanced class distribution

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/Twitter-Sentiment-Analysis-LSTM-Attention.git
cd Twitter-Sentiment-Analysis-LSTM-Attention