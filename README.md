# Intent Classification on Banking77 using PEFT

This repository contains a Google Colab notebook demonstrating how to fine-tune a **BERT-base-uncased** model on the **Banking77** dataset. To improve efficiency, we use **Parameter-Efficient Fine-Tuning (PEFT)** by freezing the base model and unfreezing only the task-specific head and the last two encoder layers.

## 🚀 Features
* **Dataset:** PolyAI Banking77 (77 intent categories).
* **Model:** BERT (Bidirectional Encoder Representations from Transformers).
* **Efficiency:** Selective layer unfreezing to reduce trainable parameters.
* **Frameworks:** Hugging Face Transformers, PEFT, and Datasets.

## 🛠️ Installation

To run this notebook locally or in your own environment, install the dependencies:

```bash
pip install -r requirements.txt
