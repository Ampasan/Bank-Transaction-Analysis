# Bank Transaction Analysis

## 📋 Deskripsi Proyek

Proyek ini merupakan analisis mendalam terhadap data transaksi bank untuk **deteksi penipuan (fraud detection)** dan **identifikasi anomali** menggunakan teknik machine learning. Dataset mencakup **2.512 sampel data transaksi** dengan berbagai atribut transaksi, demografi nasabah, dan pola penggunaan.

## 🎯 Tujuan Proyek

1. **Clustering Analysis**: Mengelompokkan nasabah berdasarkan pola transaksi mereka
2. **Classification**: Membangun model prediktif untuk klasifikasi cluster nasabah
3. **Fraud Detection**: Mengidentifikasi anomali dalam transaksi keuangan
4. **Customer Segmentation**: Segmentasi nasabah untuk strategi bisnis yang lebih baik

## 🔬 Metodologi

### 1. Data Preprocessing
- **Data Cleaning**: Menangani missing values dan duplikasi
- **Feature Engineering**: Membuat fitur binned untuk TransactionAmount dan CustomerAge
- **Encoding**: Label encoding untuk variabel kategorikal
- **Scaling**: StandardScaler untuk normalisasi data numerik
- **Outlier Handling**: Clipping outliers menggunakan IQR method

### 2. Clustering Analysis
- **K-Means Clustering**: Menggunakan Elbow Method untuk menentukan jumlah cluster optimal
- **PCA Visualization**: Reduksi dimensi untuk visualisasi cluster
- **Silhouette Score**: Evaluasi kualitas clustering

### 3. Classification Models
- **Decision Tree**: Model baseline dengan performa excellent
- **Random Forest**: Ensemble method untuk stabilitas
- **K-Nearest Neighbors (KNN)**: Dengan hyperparameter tuning
- **Logistic Regression**: Linear classifier
- **Support Vector Machine (SVM)**: Non-linear classification
- **Gaussian Naive Bayes**: Probabilistic classifier