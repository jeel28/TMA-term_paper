# 🚀 Hybrid Mixture of Experts (MoE) for Text Classification

This project implements a **Hybrid Mixture of Experts (MoE)** model for text classification using deep learning techniques. The model combines the strengths of **GRU, LSTM, and Transformer architectures** to achieve high accuracy on sentiment analysis tasks.

---

## 📌 Project Overview

Text classification is a key task in Natural Language Processing (NLP). Traditional models such as GRU, LSTM, and Transformers have their own strengths and limitations.

This project proposes a **Hybrid MoE model** that:
- Combines multiple models (experts)
- Uses a **soft aggregation strategy**
- Improves performance by leveraging strengths of each model

---

## 🧠 Model Architecture

The model consists of:

- 🔹 GRU Expert → Efficient for short sequences  
- 🔹 LSTM Expert → Handles long-term dependencies  
- 🔹 Transformer Expert → Captures complex contextual relationships  

👉 Final Output:
- Weighted combination of all expert outputs

---

## ⚙️ Technologies Used

- Python
- PyTorch
- HuggingFace Transformers
- Matplotlib
- Jupyter Notebook

---

## 📊 Dataset

- **IMDB Movie Review Dataset**
- Used for binary sentiment classification (Positive / Negative)

---

## 📈 Results

| Model | Accuracy |
|------|--------|
| GRU | 82.90% |
| LSTM | 78.00% |
| Transformer | 86.40% |
| ⭐ MoE (Proposed) | **98.60%** |

👉 The MoE model significantly outperforms individual models.

---

## 🔥 Key Features

- Hybrid deep learning architecture
- Soft Mixture of Experts (no hard routing)
- Efficient and scalable implementation
- Improved generalization

---

## 💻 Implementation

The full implementation is available in the Jupyter Notebook:

📂 `Tma_term_paper.ipynb`

---

## ▶️ How to Run

### 1. Install Dependencies
```bash
pip install torch torchvision torchaudio
pip install transformers datasets matplotlib
