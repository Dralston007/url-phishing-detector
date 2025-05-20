# URL Phishing Detector 🛡️

A machine learning-based phishing detection tool that analyzes and classifies URLs as **phishing** or **legitimate**. This project is implemented in a Jupyter Notebook and serves as a proof of concept for automated threat detection using supervised learning techniques.

## 🚀 Features

- Extracts lexical and structural features from URLs
- Trains a classifier to detect phishing attempts
- Supports evaluation metrics like accuracy, precision, recall, and F1-score
- Easy to extend with additional features or models
- Visualizations for dataset insights and model performance

## 📓 Notebook Overview

The core notebook walks through the entire detection pipeline:

1. **Data Loading**  
   Loads a labeled dataset of URLs (phishing vs. legitimate).

2. **Feature Engineering**  
   Extracts features such as:
   - URL length
   - Presence of IP address
   - Special character counts
   - Use of HTTPS or not

3. **Model Training**  
   Trains a model (e.g., Random Forest, Logistic Regression) on extracted features.

4. **Evaluation**  
   Generates confusion matrix, classification report, and other metrics.

5. **Prediction**  
   Classifies new or unseen URLs with the trained model.

## 🧠 Technologies Used

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- NumPy
- Matplotlib / Seaborn (for visualizations)
