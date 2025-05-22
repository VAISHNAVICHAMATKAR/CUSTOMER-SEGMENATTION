
# 🧠 Customer Segmentation using K-Means Clustering

This project is a web-based application that performs customer segmentation using the K-Means clustering algorithm. It analyzes customer behavior from transactional data and groups customers into segments based on RFM (Recency, Frequency, Monetary) analysis.

## 📂 Project Structure

```
CustomerSegmentation/
│
├── app.py                      # Main Flask application
├── kmeans_model.pkl           # Pre-trained KMeans model
├── OnlineRetail.csv           # Input dataset
├── Procfile                   # For deployment (Heroku)
├── requirements.txt           # Python dependencies
├── tempCodeRunnerFile.py      # Temporary script (can be removed)
│
├── static/
│   ├── ClusterId_Amount.png   # Visualization: Cluster vs Amount
│   ├── ClusterId_Frequency.png
│   └── ClusterId_Recency.png
│
└── templates/
    ├── index.html             # Homepage template
    └── results.html           # Results page template
```

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone <your-repo-url>
   cd CustomerSegmentation
   ```

2. **Install Requirements**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the App**
   ```bash
   python app.py
   ```

4. **View in Browser**
   Navigate to `http://127.0.0.1:5000/` in your browser.

## 📊 Features

- Upload transaction data (CSV)
- Perform RFM analysis
- Apply pre-trained K-Means clustering
- Visualize clusters based on Recency, Frequency, and Monetary values

## 📦 Deployment

This app includes a `Procfile`, making it suitable for deployment on **Heroku**.

## 📁 Dataset

The dataset used is `OnlineRetail.csv`, which contains e-commerce transaction data.

## ✅ Requirements

- Python 3.6+
- Flask
- Pandas
- scikit-learn
- Matplotlib / Seaborn

(See `requirements.txt` for full list)

## ✨ Credits

Developed for customer segmentation analytics using machine learning.
