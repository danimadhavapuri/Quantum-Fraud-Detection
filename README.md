# Quantum-Fraud-Detection
A novel hybrid quantum–classical machine learning framework designed to enhance the detection of collusive merchant fraud in financial systems.
# Collusion Guard: Identifying Anomalies in Transaction data using Quantum Machine Learning 

A hybrid quantum–classical machine learning framework designed to enhance the detection of collusive merchant fraud in financial systems. This project was developed for the Amaravati Quantum Valley Hackathon 2025.



# About The Project
Financial fraud has evolved into a highly sophisticated challenge, with collusive merchant fraud emerging as one of the most damaging threats. Unlike isolated incidents, this type of fraud involves groups of merchants and customers collaborating, making it difficult to detect with conventional methods.


To address this, Collusion Guard integrates the predictive accuracy of classical algorithms like XGBoost with the expressive power of quantum models, specifically Graph Neural Network (GNN) embeddings mapped into Variational Quantum Circuits (VQCs). This allows the system to model both local anomalies and global collusion structures within large-scale transaction networks.


# Key Features

Novel Hybrid Framework: A first-of-its-kind integration of Machine Learning (XGBoost) and Quantum Machine Learning (VQC) for collusion detection.



Advanced Pattern Recognition: Combines GNN embeddings with quantum circuits to capture hidden relational patterns that classical models miss.


Focus on Group Fraud: Specifically designed to detect coordinated fraud rings, not just isolated anomalous transactions.



High Accuracy: Achieved 100% accuracy in tests, significantly outperforming standalone quantum models and reducing false positives.


# Technology Stack
The project leverages the following libraries and frameworks:

Classical ML & Data Science:

Pandas, NumPy, Scikit-learn, XGBoost.docx]

Graph Analysis:

NetworkX, Node2Vec.docx]

Quantum Machine Learning:

PennyLane, Qiskit, PyTorch.docx]

Visualization:

Matplotlib, Seaborn.docx]

# Getting Started
To get a local copy up and running, follow these simple steps.

Ensure you have Python 3.10 installed.

Clone the repository.

Install the required packages by running the following command:

Bash

pip install numpy==1.23.5 pandas networkx scikit-learn matplotlib seaborn xgboost node2vec joblib pennylane pennylane-qiskit qiskit torch==1.13.1
Open the .ipynb file in Google Colab or a local Jupyter environment and run the cells in order.

Results
Our experimental evaluation demonstrated that the hybrid model significantly outperforms standalone classical approaches.

The hybrid model achieved 

100% accuracy on the test dataset.

It resulted in a 

100% reduction in false positives, which is critical for real-world fraud detection systems.

The ROC curve shows a perfect Area Under the Curve (AUC) score of 1.00.
