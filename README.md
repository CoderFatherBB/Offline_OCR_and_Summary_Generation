<div align="center">
  <h1 align="center">Offline OCR & NLP Summary Generator 📄</h1>
  <p align="center"><strong>Deep Learning Text Extraction and Summarization</strong></p>
  <p align="center">
    <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
    <img src="https://img.shields.io/badge/HuggingFace-F9AB00?style=for-the-badge&logo=huggingface&logoColor=white" />
    <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  </p>
</div>

## 📖 Overview
An advanced, fully-offline pipeline capable of extracting text from complex handwritten and digital documents using optical character recognition, and subsequently generating concise, highly-accurate summaries utilizing Transformer architectures.

## ✨ Core Features
- **High-Accuracy OCR**: Custom-trained models to handle cursive handwriting and degraded digital text.
- **Transformer-based Summarization**: Extracts key entities and generates human-readable summaries instantly.
- **Fully Offline**: Designed to operate in air-gapped environments for strict data privacy.

## 🛠️ Architecture
The system integrates state-of-the-art vision models (like TrOCR) with NLP pipelines (BART/T5) served via a lightweight Flask backend, allowing rapid inference without cloud dependencies.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
