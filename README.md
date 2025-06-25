
# 📊 Personal Projects in Machine Learning & Data Science

This repository showcases a collection of machine learning and data-driven projects that demonstrate my skills in data exploration, modeling, anomaly detection, and visualization. Each project is organized into its own directory for clarity and reproducibility.

---

## 🧠 Projects Overview

### 1. [Employee Attrition Prediction](employee_attrition/employee_attrition.ipynb)
Predicting employee turnover using HR data.

- **Goal:** Build a classification model to identify employees at risk of leaving.
- **Approach:** Feature engineering, handling class imbalance, training Random Forest and Logistic Regression models.
- **Skills Highlighted:** Classification modeling, ROC-AUC evaluation, HR analytics.

---

### 2. [Yelp Restaurant Recommendation System](yelp_recommender/Yelp_RecommendationSystem.ipynb)
Personalized content-based restaurant recommendation system and incorporated a data visualization.

- **Goal:** Recommend restaurants based on user preferences using Yelp data.
- **Approach:** Feature extraction from business attributes and reviews; cosine similarity scoring.
- **EDA Notebook:** See [EDA.ipynb](yelp_recommender/EDA.ipynb) for the data exploration and preprocessing steps.
- **Skills Highlighted:** Text processing, recommendation systems, cosine similarity, EDA, data visualization, data analysis.

---

### 3. [Sensor Anomaly Detection & Maintenance Dashboard](sensor_anomaly/anomaly_detectionML.ipynb)
Detecting anomalies in IoT sensor data and visualizing them in a dashboard.

- **Goal:** Identify abnormal sensor behavior to support proactive maintenance.
- **Approach:** Used Isolation Forest and statistical thresholds for anomaly detection.
- **Dashboard:** Real-time interactive dashboard built with [Streamlit](https://streamlit.io/) — see [maintenance_dashboard.py](sensor_anomaly/maintenance_dashboard.py).
- **Dataset:** [sensor_data.csv](sensor_anomaly/sensor_data.csv)
- **Skills Highlighted:** Time series analysis, anomaly detection, real-time monitoring, Streamlit apps.

---

## 🛠 Tech Stack

- **Languages:** Python
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, Streamlit
- **Tools:** Jupyter Notebooks, Git/GitHub, Google Colab, VS Code

---

## 🚀 Running the Projects

### Jupyter Notebooks
You can open each notebook directly in [Google Colab](https://colab.research.google.com/) or locally via Jupyter.

### Streamlit App (for anomaly dashboard)
To run the maintenance dashboard:

```bash
cd sensor_anomaly
streamlit run maintenance_dashboard.py
