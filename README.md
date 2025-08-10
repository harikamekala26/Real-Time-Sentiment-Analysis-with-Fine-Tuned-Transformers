# Real-Time-Sentiment-Analysis-with-Fine-Tuned-Transformers

## 📌 Project Overview
This repository contains a **GPU-optimized fine-tuning pipeline** for sentiment analysis using the **Hugging Face Transformers** library.  
The project demonstrates how to fine-tune a pre-trained transformer model for binary sentiment classification (**positive / negative**) on a custom dataset.

## 🚀 Features
- **GPU-Accelerated Training** in Google Colab.
- **Fine-tuning** using Hugging Face `Trainer` API.
- **Custom Label Mapping** (`LABEL_0` → `negative`, `LABEL_1` → `positive`).
- **Evaluation Metrics** (Accuracy, Loss tracking).
- **Real-time Inference Script** for interactive sentiment prediction.
- **Model Export & Loading** from local path.

---

## 📊 Training Results

| Epoch | Training Loss | Validation Loss | Accuracy (%) |
|-------|---------------|-----------------|--------------|
| 1     | 0.1384        | 0.1614          | 94.72        |
| 2     | 0.0978        | 0.1938          | 94.03        |
| 3     | 0.1059        | 0.1988          | 94.49        |

---

## 🧪 Evaluation & Example Predictions

**Evaluation Accuracy:** `94.72%`

### Example:
```text
Enter text: I love this product!
Sentiment: positive (score: 0.97)



