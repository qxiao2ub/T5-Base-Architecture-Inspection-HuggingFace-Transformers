# T5-Base Architecture Inspection HuggingFace Transformers


---

## 🚀 Overview

This project is structured into three main components:

### 1️⃣ T5 Architecture Inspection
- Load and analyze `t5-base`
- Extract configuration parameters
- Inspect encoder blocks
- Understand multi-head attention

👉 Focus: **Model interpretability & architecture understanding**

---

### 2️⃣ Fine-Tuning for Summarization
- Data preprocessing (news dataset)
- Tokenization with Hugging Face
- Training with `Seq2SeqTrainer`
- Evaluation using ROUGE metrics

👉 Focus: **End-to-end training pipeline**

---

### 3️⃣ Model Comparison
- Pretrained vs Fine-tuned T5
- Generate summaries
- Compare outputs qualitatively & quantitatively

👉 Focus: **Performance benchmarking**

---

## 🧰 Tech Stack

- Python 3.x
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- ROUGE Evaluation (`evaluate`, `rouge_score`)
- NLTK

---

## ⚙️ Installation

```bash
pip install transformers datasets evaluate rouge_score nltk torch pandas
