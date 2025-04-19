# DA6401_Assignment2
# Part A - CNN Training from Scratch

## Overview
This part of the assignment involves training a Convolutional Neural Network (CNN) from scratch on the iNaturalist dataset for a multi-class classification task. The objective is to explore different architectural and training strategies, perform hyperparameter tuning, and visualize learned features and failure cases.

---
Report link :https://wandb.ai/me21b118-iit-madras/da6401-assignment2/reports/DA6401-Assignment-2--VmlldzoxMjM2NTE3Mw?accessToken=u393jw1r01h34xfcecz3cg6wquos31v3md440ydnt014fnzvlhk8tvlgnyfw01oc
---

## Setup Instructions

 Install dependencies:
   ```bash
   pip install torch torchvision torchinfo wandb
   ```


## Hyperparameter Tuning
- We performed sweep-based hyperparameter tuning using wandb.
- Best model configuration :
  - Learning Rate: 0.001
  - dense_neurons : 128
  - Epochs: 10

---

---

