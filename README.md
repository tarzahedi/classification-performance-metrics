# Classification Performance Metrics

## Overview

This project uses **Logistic Regression** to classify data. It shows how to preprocess data, tune the model, and evaluate it using different performance metrics beyond just accuracy.

## Why Different Metrics Matter

- **Accuracy** measures overall correctness but can be misleading if classes are imbalanced.
- **Precision** is important when false positives are costly (e.g., spam filters mistakenly blocking good emails).
- **Recall** matters when missing positives is dangerous (e.g., failing to detect a disease).
- **F1-score** balances precision and recall when both false positives and false negatives are important.

It's important to understand the difference between different metrics and know how to interpret them.

## Installation

```bash
git clone https://github.com/tarzahedi/classification-performance-metrics.git
cd classification-performance-metrics
python -m venv env
source env/bin/activate  # macOS/Linux
# or
env\Scripts\activate     # Windows
pip install -r requirements.txt
```
