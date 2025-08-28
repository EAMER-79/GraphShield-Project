# GraphShield: Dynamic Malware Detection via Temporal API Graph Analysis

**GraphShield** is a graph-based malware detection framework that analyzes dynamic API call sequences with high precision. It converts API calls into temporal graphs, applies semantic vectorization, and uses attention mechanisms to capture both short-term actions and long-term behavioral patterns, representing a significant improvement over prior approaches.

## 🧠 Methodology

Our framework leverages advanced Graph Neural Network (GNN) architectures to model the structural and temporal features of execution traces. We evaluate a comprehensive suite of models, including:

*   **Graph Convolutional Networks (GCNs)**
*   **Graph Attention Networks (GATs)**
*   **Graph Isomorphism Networks (GINs)**
*   **Hybrid Transformer-based models** that combine convolutional, recurrent, and autoencoding layers.

This multi-architectural approach supports both classification-only and combined classification-reconstruction strategies for robust feature learning.

## 📊 Datasets

The model was trained and evaluated on large-scale, balanced datasets to ensure unbiased learning and evaluation.

*   **Training Dataset (Dataset 1):**
    *   $300,000$ samples ($150,000$ malware + $150,000$ goodware).
*   **Testing Dataset (Dataset 2):**
    *   $200,000$ samples ($100,000$ malware + $100,000$ goodware).

### External Validation

To ensure generalizability, GraphShield was rigorously tested against two external datasets:
*   **Dataset 3** \cite{ceschin2018need}
*   **Dataset 4** \cite{ki2015novel}

## 🔐 Data Access

Access to the primary datasets used for training (Dataset 1) and testing (Dataset 2) is available upon request to ensure responsible use.

Please fill out our [Data Access Request Form](https://forms.gle/vcKXSEBsTjWZa23NA) to get started.

## 🚀 Getting Started

