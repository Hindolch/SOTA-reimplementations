# GRU in PyTorch (from scratch)

Trained a GRU model built from scratch using only PyTorch’s basic modules.

---

## ModelArgs / Hyperparameters

| Parameter     | Value   | Description                            |
| ------------- | ------- | -------------------------------------- |
| batch\_size   | 32      | Batch size                             |
| hidden\_size  | 46      | GRU hidden units (as per paper)        |
| num\_layers   | 2       | Stacked GRU layers                     |
| dropout       | 0.3     | Dropout for regularization             |
| weight\_noise | 0.075   | Gaussian noise added to weights        |
| epochs        | 100     | Max epochs (early stopping used)       |
| lr            | 1e-3    | Initial learning rate (with scheduler) |
| optimizer     | RMSprop | Optimizer                              |

---

## Epochs / Steps

* Train epochs: 100
* Validation: every epoch
* Early stopping + LR scheduling applied

---

## Losses (Negative Log-Likelihood)

| Metric    | Value  |
| --------- | ------ |
| Train NLL | \~4.56 |
| Val NLL   | \~5.90 |
| Test NLL  | \~6.01 |

![Screenshot from 2025-07-07 17-34-28](https://github.com/user-attachments/assets/8d1fcf34-cb83-4501-8446-7383c66c5231)


---

