# LSTM in PyTorch (from scratch)

Trained an LSTM model built from scratch using only PyTorch’s native modules. Logged everything using MLflow.

---

## ModelArgs / Hyperparameters

| Parameter     | Value   | Description                            |
| ------------- | ------- | -------------------------------------- |
| batch\_size   | 32      | Batch size                             |
| hidden\_size  | 64      | LSTM hidden units                      |
| num\_layers   | 1       | Number of stacked LSTM layers          |
| dropout       | 0.2     | Dropout for regularization             |
| block\_size   | 50      | Sequence length used as input          |
| epochs        | 10      | Total training epochs                  |
| lr            | 1e-3    | Learning rate                          |

---

## Epochs / Steps

* Trained till: 10 epochs
* Validation: every epoch
* MLflow used to log train/val loss

---

## Losses (MSE)

| Metric     | Value   |
| ---------- | ------- |
| Train MSE  | ~0.0006 |
| Val MSE    | ~0.0001 |

<img width="1889" height="397" alt="Screenshot from 2025-07-14 13-02-58" src="https://github.com/user-attachments/assets/764081ec-57bd-4bbd-a5bc-cdffa923395e" />

<img width="1728" height="582" alt="Screenshot from 2025-07-14 12-58-51" src="https://github.com/user-attachments/assets/cfa20808-95b8-4f90-9e59-8ad95da2b6ee" />


---
