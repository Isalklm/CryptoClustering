# 📊 Cryptocurrency Clustering Analysis

## 📂 Files and Folder Structure

### 📌 Data Preparation
- **crypto_market_data.csv**: Dataset containing cryptocurrency price change percentages.
- **Crypto_Clustering.ipynb**: Jupyter Notebook containing all analysis and visualizations.

### 📌 Analysis Steps
- **Finding the Best k Using the Original Scaled DataFrame**
- **Clustering with K-Means Using the Original Scaled DataFrame**
- **Optimizing Clusters with PCA**
- **Finding the Best k Using the PCA DataFrame**
- **Clustering with K-Means Using the PCA DataFrame**
- **Visualizing and Comparing Results**

## 🎯 Project Overview
This project applies **Principal Component Analysis (PCA)** and **K-Means clustering** to analyze and segment cryptocurrencies based on their market performance. 

### 🔍 Key Features:
- **Elbow Method**: Determine the optimal number of clusters using the inertia values.
- **K-Means Clustering**: Apply clustering on both original and PCA-transformed data.
- **Principal Component Analysis (PCA)**: Reduce data dimensionality while preserving variance.
- **Comparison of Results**: Evaluate clustering effectiveness before and after applying PCA.

## 🛠 Technologies Used
- **Python**: Primary programming language.
- **Pandas & Scikit-Learn**: Data processing, manipulation, and machine learning (K-Means, PCA).
- **HvPlot & Panel**: Interactive data visualization and layout management.
- **Matplotlib**: Standard plotting library.

## 📊 Dataset
The dataset used in this analysis includes:
- **Price Change Percentage**: Cryptocurrency price fluctuations over different time periods.
- **Market Volatility**: Representation of price stability and movements.
- **Coin Identifiers**: Specific cryptocurrency tickers and indexing.
- **Time Frames**: Various time windows analyzed for trends.

## 📝 Instructions
1. Open **Crypto_Clustering.ipynb** in Jupyter Notebook to execute the code step by step.
2. Run each cell sequentially to perform data cleaning, transformation, PCA, K-Means clustering, and visualization.
3. Compare the cluster results before and after PCA transformation.

## 🔗 Attribution and Code Sources
This project was developed as part of a bootcamp program. Class materials, documentation, and external resources were used to complete this challenge. The dataset and methodologies integrate:
- **Machine learning and clustering techniques from Scikit-Learn**
- **Data visualization with HvPlot, Panel, and Matplotlib**
