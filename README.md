# Homework 5 – What Happens in Vegas, Stays in Venmo

This project explores peer-to-peer transaction data on Venmo using PySpark, graph analytics, and deep learning techniques. It includes four core parts:

## 📊 Part 1: Text Analytics
- Classified Venmo transaction descriptions using emoji and word dictionaries
- Built static and dynamic spending profiles
- Used LLaMA-3 embeddings + clustering for topic discovery
- Compared model-based vs. rule-based category mapping

## 🧑‍🤝‍🧑 Part 2: Social Network Analysis
- Extracted users’ friends and friends-of-friends
- Computed network metrics (degree, clustering coefficient, PageRank)
- Modeled user network evolution over 12 months

## 📈 Part 3: Predictive Analytics with MLlib
- Engineered RFM-style features
- Trained three models (RF, RF + behavior, RF + network)
- Analyzed MSE progression over user lifetime

## 🧠 Part 4: Graph Neural Networks
- Trained a GCN on the Cora citation dataset
- Compared graph vs. non-graph feature performance
- Visualized learned embeddings with t-SNE

---

### 🛠 Tools Used
- PySpark, NetworkX, GraphFrames, Hugging Face (LLaMA-3), scikit-learn, torch_geometric

👩‍💻 Author: Shivani Tayade  
📅 Spring 2025, UC Davis MSBA
