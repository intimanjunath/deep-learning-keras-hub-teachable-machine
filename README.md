# 🤖 Deep Learning Assignment – Teachable Machine & Keras Hub Demos

**Tools Used:** Teachable Machine, TensorFlow, Keras, TensorFlow Hub, NLTK, Hugging Face Transformers  
**Runtime:** Google Colab (GPU/CPU)

---

## 🧩 Overview

This repository contains the complete implementation of a deep learning assignment covering:

- ✅ Task (a): Teachable Machine examples (Image, Pose/Video, Simulated Text)
- ✅ Task (b): Keras Hub examples (Image + Text models from Easy to Expert)

Each model is demonstrated, tested, and visualized clearly in separate Colab notebooks, including intermediate outputs, predictions, and model summaries.

---

## 📁 Task (a): Teachable Machine Models

| Type     | Title                                 | Description |
|----------|---------------------------------------|-------------|
| 🖼️ Image   | **Human vs Object Classifier**        | Teachable Machine model trained using webcam images of human faces and objects. Tested with Keras-compatible model export (`model.json`, `weights.bin`). |
| 🎥 Video   | **Pose Classification via MoveNet**   | Teachable Machine pose model for "Standing" vs "Arms Raised", using MoveNet to extract keypoints and Logistic Regression to classify. |
| 📝 Text    | **Simulated Text Classification**     | Simulated text classification using Universal Sentence Encoder embeddings + Logistic Regression in Colab. |

> ✅ All relevant assets (`.tm`, `.json`, `.bin`, `metadata.json`, and sample `.png` images) are included.

---

## 📁 Task (b): Keras Hub Demos

### 🧠 Image Models

| Level        | Model                            | Dataset        | Highlights |
|--------------|----------------------------------|----------------|------------|
| ✅ Easy       | MobileNetV2 Feature Extractor    | MNIST          | Pretrained MobileNet + dense classifier |
| ✅ Intermediate | Custom CNN                     | KMNIST          | 2-layer CNN on fashion-like characters |
| ✅ Advanced   | Multi-label MobileNetV2          | Fashion MNIST  | One-hot labels + sigmoid activation |
| ✅ Expert     | SSD MobileNet V2 (TF Hub)        | Built-in image | Object detection + bounding boxes |

---

### 📚 Text Models

| Level        | Model                            | Dataset        | Highlights |
|--------------|----------------------------------|----------------|------------|
| ✅ Easy       | Embedding + Dense Sentiment Net | Custom (4 samples) | Tokenizer + average pooling |
| ✅ Intermediate | BERT Fine-tuning (TF Hub)     | Custom (4 samples) | bert_en_uncased_L-12_H-768_A-12 |
| ✅ Advanced   | NLTK Named Entity Recognition    | News Paragraph | POS + Chunking |
| ✅ Expert     | T5 Summarization (Transformers)  | AI Paragraph   | HuggingFace `t5-small` pipeline |

---

## 🎬 YouTube Walkthrough

Each model and notebook is demonstrated in a 1-minute walkthrough with:
- Dataset explanation
- Model architecture
- Evaluation & metrics
- Output predictions / visualizations

🖇️ [Watch the full demo here]([https://www.youtube.com/watch?v=SxxhdlU-2a4])

