# London Airbnb Price Prediction (NLP Project)

This project predicts property prices for Airbnb listings in London by leveraging diverse features in the dataset, with a special focus on the **text data**.  
It demonstrates the full workflow of data analysis: exploratory data analysis (EDA), preprocessing, feature engineering, model building, and evaluation.

---

## Table of Contents
1. Introduction  
2. Data Loading and Exploratory Data Analysis  
3. Data Preprocessing, Feature Engineering, and Feature Selection  
   - Missing value imputation (KNN Imputer)  
   - Feature engineering for structured data  
   - Feature selection for non-text features  
   - Text preprocessing and embedding  
4. Model Selection  
   - Benchmark models (Linear Regression, Random Forest, LightGBM, Basic GRU)  
   - Neural network models (GRU, LSTM, TextCNN)  
   - Comprehensive model architecture  
5. Application to Test Set  
6. Conclusion  

---

## Project Overview
- **Goal**: Predict Airbnb listing prices in London.  
- **Dataset**: Airbnb listings data (train + test sets with structured and text features).  
- **Challenge**: Handling missing values, high-dimensional features, and extracting meaningful information from listing descriptions.  

---

## Methods
- **Data Preprocessing**
  - KNN imputation for missing values in host response and review score features  
  - Borough-level feature engineering from location data  
  - Text preprocessing and feature extraction (NLP techniques)  

- **Models Implemented**
  - Baselines: Linear Regression, Random Forest, LightGBM  
  - Deep Learning: GRU, LSTM, TextCNN  
  - Final comprehensive architecture combining text + non-text features  

- **Evaluation**
  - Models compared on predictive performance (RMSE, R²)  
  - Best model selected and applied to test set  

---

## Results
- Significant improvement over baseline models by integrating NLP-derived features.  
- Neural network architectures (GRU, LSTM, TextCNN) demonstrated the strongest ability to capture textual signals from listing descriptions.  
- Final model provided competitive predictions for Airbnb prices across London.  

---

## Files
- `airbnb-price-prediction-nlp.ipynb` — main Jupyter Notebook with full workflow  

---

## Tech Stack
- **Languages/Tools**: Python, Jupyter Notebook  
- **Libraries**: Pandas, NumPy, scikit-learn, LightGBM, TensorFlow/Keras, Matplotlib/Seaborn  

---

## Key Takeaways
- Demonstrates end-to-end machine learning workflow.  
- Shows ability to integrate **structured data + NLP features**.  
- Highlights hands-on experience with both **traditional ML** and **deep learning models**.  

---
