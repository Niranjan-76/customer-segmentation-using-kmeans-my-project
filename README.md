
# 🧠 Customer Segmentation using KMeans & Streamlit

This project segments customers into distinct groups using KMeans Clustering based on their demographics and shopping behavior. It also features a **Streamlit web app** for predicting customer segments interactively.

## 🚀 Features

- Clusters customers using **KMeans algorithm**
- Human-friendly labels like “High-Value Shoppers”, “Budget-Conscious Browsers”
- Real-time prediction using a **Streamlit web app**
- Uses demographic and behavioral data: Age, Income, Spending, Web/Store Purchases, Recency
- Visualizes cluster summaries via heatmaps and tables

---

## 📂 Project Structure

customer-segmentation-app/
│
├── README.md                   ← This file
├── requirements.txt            ← Python dependencies
├── app.py                      ← Streamlit web app
├── Analysis_Model.ipynb        ← Jupyter notebook
├── customer_segmentation.xlsx  ← Dataset
├── kmeans_model.pkl            ← Trained model
├── scaler.pkl                  ← Scaler used for prediction
├── cluster_summary.csv         ← Cluster means summary
├── sample_input.csv            ← Sample format for app input

---

## 📊 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Streamlit
- Seaborn, Matplotlib
- Joblib

---

## 🧪 How to Run the Project

1. **Clone the repository**
```bash
git clone https://github.com/your-username/customer-segmentation-app.git
cd customer-segmentation-app
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the Streamlit app**
```bash
streamlit run app.py
```

---

## 🧩 Cluster Descriptions

| Cluster | Label                             | Description |
|---------|-----------------------------------|-------------|
| 0       | High-Value Active Shoppers        | High income and spending; frequent online and store purchases |
| 1       | Budget-Conscious Older Browsers   | Older, low-spending users who browse often but purchase less |
| 2       | Frequent Browsers, Low Spenders   | Younger users who visit frequently but rarely buy |
| 3       | Senior High-Value Buyers          | Older users with high income and high spending |
| 4       | Multi-Channel Frequent Shoppers   | Very active users across web and store; above average spend |
| 5       | Recent Low Spenders / Anomaly     | Recent low-spending users, possibly outliers |

---

## 📷 Screenshot

![screenshot](<img width="782" height="845" alt="image" src="https://github.com/user-attachments/assets/ae9d4b09-df09-466f-abda-3834c15090ae" />
)

---

## ✍️ Author

- **Niranjan S**
- [LinkedIn]([https://linkedin.com/in/yourprofile](https://www.linkedin.com/in/niranjan53/))


---

## 📌 Note

This project is part of a portfolio to demonstrate skills in data preprocessing, clustering, model deployment using Streamlit, and customer segmentation using unsupervised learning.

---

⭐ If you like this project, give it a star!
