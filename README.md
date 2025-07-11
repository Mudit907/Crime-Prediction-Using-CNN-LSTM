# 🧠 Crime Forecasting with Deep Learning (LSTM & CNN-LSTM)

This repository contains the full implementation and evaluation code for our research paper:  
**"Spatio-Temporal Crime Prediction Using Deep Learning-A CNN-LSTM based approach"** (2024).

## 📌 Overview

We predict daily crime counts using deep learning models (LSTM and CNN-LSTM) trained on the Chicago Crime Dataset (2001–2023).  
Our final model achieves an RMSE of **0.0281** and an R² of **0.9802**.

Dataset : https://www.kaggle.com/datasets/nathaniellybrand/chicago-crime-dataset-2001-present

## 🚀 Models

- ✅ Hyperparameter-Tuned LSTM
- ✅ CNN-LSTM Hybrid Model
- ✅ Ablation Study on Sequence Lengths

## 📊 Results

| Model | RMSE | MAE | R² Score |
|-------|------|-----|----------|
| LSTM | 0.0515 | 0.0122 | 0.9802 |
| CNN-LSTM | 0.0281 | 0.0122 | 0.9802 |

## 📁 Project Structure

- `notebooks/` — Google Colab
- `src/` — Modular code (preprocessing, training, evaluation)
- `models/` — Trained `.h5` model files
- `results/` — Output plots and metrics
- `data/` — Sample data (do not upload full raw dataset)
- `README.md` — This file

## 📦 Requirements

```bash
pip install -r requirements.txt
