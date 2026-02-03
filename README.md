# 🛡️ Collusion Guard: Triple Hybrid Fraud Detection
### Identifying Anomalies in Transaction Data using GNN, XGBoost, and Quantum Machine Learning 

**Collusion Guard** is a cutting-edge triple-hybrid framework designed to enhance the detection of collusive merchant fraud in financial systems. This project was originally developed for the **Amaravati Quantum Valley Hackathon 2025** and has been upgraded to a more robust, deep-relational architecture.

## 🌟 About The Project
Financial fraud has evolved into a highly sophisticated challenge, with **collusive merchant fraud** emerging as one of the most damaging threats. Unlike isolated incidents, this fraud involves groups of merchants and customers collaborating in circular patterns (money laundering loops), making it nearly invisible to conventional methods.

To address this, **Collusion Guard** integrates three distinct mathematical approaches:
1.  **GNN (Graph Neural Network):** Extracts deep structural "collusion" features by analyzing the relationships between transaction nodes.
2.  **XGBoost (Classical ML):** Leverages the GNN embeddings to provide high-precision statistical classification.
3.  **VQC (Quantum Machine Learning):** Maps GNN embeddings into a **Variational Quantum Circuit (VQC)** using PennyLane to capture hidden relational patterns in high-dimensional Hilbert Space.

## 🚀 Key Features
* **Novel Triple Hybrid Framework:** A unique integration of **GNN**, **XGBoost**, and **QML (VQC)** for multi-layered fraud detection.
* **Deep Relational Recognition:** Combines the message-passing power of GNNs with quantum circuits to find patterns that standard models miss.
* **Focus on Group Fraud:** Specifically engineered to detect coordinated fraud rings and circular transaction loops.
* **High-Performance Results:** Achieved near-perfect accuracy in tests, significantly outperforming standalone classical or quantum models.

## 🛠️ Technology Stack
* **Graph Intelligence:** NetworkX, PyTorch Geometric (GNN).
* **Classical ML & Data Science:** Pandas, NumPy, Scikit-learn, XGBoost.
* **Quantum Machine Learning:** PennyLane, PyTorch.
* **Visualization:** Matplotlib, Seaborn.

## 🏁 Getting Started
To get the Triple Hybrid model up and running, follow these steps:

1.  **Environment:** Ensure you use **Python 3.11** (Recommended: Google Colab **2025.10** runtime).
2.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/Quantum-Fraud-Detection.git](https://github.com/your-username/Quantum-Fraud-Detection.git)
    ```
3.  **Install the Modern Stack:**
    *(Note: We have removed strict version pinning to prevent binary incompatibility errors)*
    ```bash
    pip install pennylane torch-geometric xgboost joblib numpy pandas networkx scikit-learn matplotlib seaborn
    ```
4.  **Execute:** Open the `.ipynb` file in Google Colab, **Restart the Session** after installation, and run all cells.

## 📊 Results
Our experimental evaluation proves that the **Triple Hybrid** approach offers superior detection capabilities:
* **100% Accuracy:** Achieved on synthetic test datasets specifically modeling collusive loops.
* **Zero False Positives:** Critical for financial systems to avoid blocking legitimate users.
* **Perfect AUC:** The ROC curve demonstrates an Area Under the Curve (AUC) score of **1.00**.
