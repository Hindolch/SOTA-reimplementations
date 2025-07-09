# GPT in PyTorch

Implemented a GPT-style Transformer from scratch using PyTorch and trained it on the TinyShakespeare dataset.

Inspired by the paper:
**[Improving Language Understanding by Generative Pre-Training (GPT-1)](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf)**

---

## 🔢 Model Details

| Component       | Value                      |
| --------------- | -------------------------- |
| Context Size    | 32                         |
| Layers          | 4                          |
| Heads per Layer | 4                          |
| Embedding Dim   | 64                         |
| Optimizer       | AdamW                      |
| Loss            | CrossEntropy               |
| Tokenizer       | TikToken (GPT-2 BPE)       |
| Sampling        | Temperature + Top-k (k=40) |

---

## 📉 Final Loss

| Metric | Value |
| ------ | ----- |
| Train  | 2.86  |
| Val    | 5.69  |

---

## 🛠 Frameworks Used

* PyTorch
* TikToken

---

## 📝 Output

Generates Shakespeare-like text autoregressively using top-k sampling.




