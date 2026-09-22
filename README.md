# FedFinGuard: Trust-Aware Federated Learning with Prototype Contrastive Attention for Adversarially Robust Financial Fraud Detection

This is the official implementation of the proposed **FedFinGuard** framework in the paper  
**"Trust-Aware Federated Learning with Prototype Contrastive Attention for Adversarially Robust Financial Fraud Detection"**.

The model was trained and tested on two widely used financial datasets: **European Credit Card Fraud** and **Taiwan Credit Card Default**.

If you want to use the original datasets, please refer to the links below:
1. European Credit Card Fraud (Kaggle / ULB): https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud  
2. Taiwan Credit Card Default (UCI Machine Learning Repository): https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients

---

## Framework
![alt text](https://github.com/Musaed98/FedFinGuard/blob/main/framework.png?raw=true)
*(Note: Please update this image link to match the actual path in your repository)*

---

## Requirements
1. Python 3.8+
2. PyTorch 1.8.0+
3. NumPy
4. Pandas
5. Scikit-learn
6. Matplotlib
7. TQDM
8. XGBoost (required for baseline comparison reproductions)

---

## Quick Start

### Installation
```bash
git clone https://github.com/Musaed98/FedFinGuard.git
cd FedFinGuard
pip install -r requirements.txt
