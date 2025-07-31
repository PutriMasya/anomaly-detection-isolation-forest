# anomaly-detection-isolation-forest

# 🛡️ Anomaly Detection in Credit Card Transactions using Isolation Forest

This project applies Isolation Forest, an unsupervised machine learning algorithm, to detect anomalies (potential frauds) in credit card transactions.

## 📊 Dataset
- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Contains anonymized features (V1–V28), `Time`, `Amount`, and a label `Class`.

## 🧠 Method
- **Model**: Isolation Forest from Scikit-Learn
- **Contamination Rate**: 0.1%
- **Preprocessing**: Dropped `Time` and `Class`, scaled `Amount` using StandardScaler.

## 📈 Result
- Detected ~492 potential anomalies from ~284,000 transactions.
- Visualized distribution of anomalies using histograms and scatter plots.

## 📷 Visualizations
- `visualizations/histogram_normal.png`
- `visualizations/histogram_anomaly.png`
- `visualizations/scatter_time_amount.png`

## 💻 Tools Used
- Python (Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib)
