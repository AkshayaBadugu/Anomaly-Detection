
# 🧠 User Behavior Anomaly Detection System

## 📌 Overview
The **User Behavior Anomaly Detection System** is a machine learning project designed to identify and flag unusual user login behaviors based on historical data. It aims to detect potential cybersecurity threats such as unauthorized access, fraud, or compromised accounts by learning and profiling normal user login patterns.

---

## 🎯 Project Goals
- Detect anomalous user login activities.
- Use data preprocessing, feature engineering, and ML models to identify deviations.
- Visualize user behavior and outlier insights for better interpretability.

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `cyber.ipynb` | Main Jupyter notebook: data loading, processing, model training, and visualization of anomalies. |
| `anomaly_detected_logins_large.csv` | Dataset containing user login event details (user ID, timestamp, location, device, login status, etc.). |

---

## ⚙️ How to Run

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/user-anomaly-detection.git
cd user-anomaly-detection
```

2. **Install Dependencies**
```bash
pip install -r requirements.txt
```

3. **Launch the Jupyter Notebook**
```bash
jupyter notebook cyber.ipynb
```

> 📌 Make sure `anomaly_detected_logins_large.csv` is in the same directory as the notebook.



## 🧪 Methodology

1. **Data Collection** – Login logs with user details and timestamps.
2. **Preprocessing** – Handle missing values, encode categories, normalize values.
3. **Feature Engineering** – Generate features like login frequency, time gaps, location changes.
4. **Model Training** – Use anomaly detection algorithms such as:
   - Isolation Forest
   - Local Outlier Factor (LOF)
   - One-Class SVM
5. **Evaluation & Visualization** – Use F1-Score (if labeled) or analyze anomaly scores to assess performance and plot anomalies.

---

## 🛠 Tech Stack

- Python 3.x  
- Jupyter Notebook  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  


## 📈 Applications

- **Cybersecurity** – Detect unauthorized or suspicious logins.
- **Fraud Detection** – Catch fraud in banking or e-commerce logins.
- **System Monitoring** – Identify abnormal usage patterns.
- **User Analytics** – Improve user experience by understanding unusual behaviors.


## 👤 Author

**Akshaya**  
🔗 [GitHub](https://github.com/AkshayaBadugu)  
🔗 [LinkedIn](www.linkedin.com/in/akshaya-badugu-224a45266)
