# 🏏 IPL Match Outcome Prediction – Full Stack Analytics Project

This project is a complete sports analytics pipeline developed over three phases, focusing on predicting match outcomes in the Indian Premier League (IPL). It combines data exploration, classical machine learning, and deep learning using Python libraries such as Pandas, Scikit-learn, and PyTorch. 

---

## 📁 Project Structure

- **TP01 – Pandas Module**: Data cleaning, feature engineering, and visual exploration
- **TP02 – Scikit-learn Module**: Classical machine learning with supervised & unsupervised models
- **TP03 – PyTorch Module**: Deep learning implementation for multi-class match outcome prediction

---

## 📊 TP01: Data Analysis with Pandas

- Explored a rich IPL dataset with match, team, and player-level data
- Performed preprocessing: date parsing, missing value imputation, feature creation (e.g. match duration, win margin)
- Created visualizations using Matplotlib and Seaborn:
  - Match result types
  - Victory margin by team
  - Word cloud of frequent "Player of the Match"
- Output: Cleaned and transformed DataFrame ready for ML modeling

---

## 🤖 TP02: Machine Learning with Scikit-learn

- Applied label encoding, one-hot encoding, and feature scaling
- Supervised models: Logistic Regression, Decision Tree, Random Forest
- Unsupervised learning: K-Means clustering of team scores
- Evaluation metrics: Accuracy, F1-score, Confusion Matrix
- Output: Trained ML models and insights for comparative performance

---

## 🧠 TP03: Deep Learning with PyTorch

- Defined a fully connected neural network (`IPLNet`) using PyTorch
- Preprocessed data using `LabelEncoder`, `StandardScaler`, and `TensorDataset`
- Training configuration:
  - Batch size: 32
  - Epochs: 20–50
  - Loss function: CrossEntropyLoss
  - Optimizer: Adam
- Evaluation:
  - Accuracy, Confusion Matrix, F1-score
  - Multi-class AUC-ROC (One-vs-Rest strategy)
  - Visual analysis: ROC curves, loss plots, prediction confidence
- Output: End-to-end predictive pipeline using modern AI techniques

---

## 📌 Key Takeaways

- A complete journey from raw structured IPL data to deep learning deployment
- Evaluation shifted from accuracy to more robust metrics like ROC-AUC
- Demonstrated real-world application potential in fantasy sports, broadcast insights, and sports management

---

## 🧩 Future Enhancements

- Add LSTM/Transformer models for temporal and sequential modeling
- Include player-level statistics for finer granularity
- Enable live match prediction with streaming data
- Integrate team/venue embeddings for contextual awareness

---

## 📚 References

The project is backed by a diverse set of resources, including:
- *Python for Data Analysis* – Wes McKinney
- *Hands-On Machine Learning* – Aurélien Géron
- *Deep Learning with Python* – François Chollet
- PyTorch and Scikit-learn official docs
- Kaggle’s IPL dataset and IPL T20 official site

---

## 👥 Team Members

- Ashwin  
- Akarsh  
- Divakar  
- Sara
