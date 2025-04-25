# EMRIL
Built a dynamic classification system for imbalanced, evolving data using reinforcement learning to select the best model in real-time. Integrated concept drift detection, base learner ensembles, and a SQLite memory module to improve accuracy and adaptability.
# EMRIL: Ensemble Method with Reinforcement Learning for Imbalanced Drifting Data Streams

EMRIL is a robust classification framework designed to handle **concept drift** and **class imbalance** in real-time data streams. It intelligently combines multiple base classifiers with a **Reinforcement Learning (RL)** agent that dynamically selects the best-performing model based on the current data context.

## 🚀 Key Features

- ✅ **Reinforcement Learning Agent (Q-learning)** for dynamic model selection
- 🔁 **Concept Drift Handling** using sliding window techniques
- ⚖️ **Imbalanced Data Support** with ensemble methods
- 🧠 **Base Learners**: Hoeffding Tree, Naive Bayes, k-NN, Random Forest
- 🗃️ **SQLite-based Memory** to persist model performance across time
- 📊 **Evaluation Metrics**: Accuracy, F1-score, G-Mean, Processing Time

## 🧪 How It Works

1. Streaming data arrives in chunks (batches).
2. Drift detection monitors changes in data distribution.
3. The RL agent (Q-learning) selects the best classifier for each chunk.
4. Results are stored in a local SQLite database for feedback and performance tracking.
5. Ensemble is updated adaptively to handle evolving data.

## 🛠️ Technologies Used

- Python
- scikit-learn
- River (for stream learning)
- SQLite
- pandas, numpy, matplotlib
- Jupyter Notebook



