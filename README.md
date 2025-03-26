# NYCU Selected Topics in Visual Recognition using Deep Learning 2025 Spring HW1

**Student ID**: 313551818  
**Name**: Marie Picquet

---

## Introduction

This repository contains the implementation for Homework 1: Image Classification with ResNet-50. The goal is to fine-tune a pretrained ResNet-50 model for a 100-class classification task using PyTorch.

The model is trained with data augmentation, weighted cross-entropy loss, and label smoothing. It was evaluated using accuracy, loss, and a normalized confusion matrix. The final model achieved a competition score of 89\% on the test set.

---

## How to Install

1. Clone the repository or open the notebook in Google Colab.  
2. The code was tested using the following environment:
   - Python 3.10+
   - PyTorch (>=1.13)
   - torchvision
   - numpy
   - scikit-learn
   - matplotlib
   - seaborn

If running locally, install dependencies with:

```bash
pip install -r requirements.txt
```
3. Update the paths in the notebook if necessary:

  train_path = './data/train'
  val_path = './data/val'
  test_path = './data/test'

4. Performance Snapshot

Final validation accuracy: ~86%
Competition test score: 89%
