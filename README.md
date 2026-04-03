# Fake-News-Detection-ML-Streamlit-App

## 1. Overview
This project implements a machine learning-based system to classify news articles as real or fake. It includes an interactive Streamlit web application that allows users to test models and visualize performance in real time.

## 2. Objective
1. Build a classification system to detect fake news  
2. Compare multiple machine learning models  
3. Provide an interactive interface for user input and analysis  

## 3. Problem Statement
The rapid spread of misinformation requires automated systems to identify fake news efficiently. This project addresses the problem using supervised machine learning techniques.

## 4. Dataset
1. Total Records: 20,000 news articles  
2. Features:
   - Title  
   - Text  
   - Date  
   - Source  
   - Author  
   - Category  
3. Target Variable: Real or Fake  

## 5. Models Used
1. Logistic Regression  
2. Random Forest  
3. Perceptron  
4. K-Nearest Neighbors  
5. Decision Tree  

## 6. Methodology
1. Data preprocessing and encoding  
2. Train-test split (70:30)  
3. Model training using multiple classifiers  
4. Performance evaluation using standard metrics  
5. Deployment using Streamlit  

## 7. Evaluation Metrics
1. Accuracy  
2. Precision  
3. Recall  
4. Confusion Matrix  
5. ROC Curve  
6. Precision-Recall Curve  

## 8. Results
1. Random Forest achieved the best overall performance  
2. Logistic Regression provided good interpretability  
3. KNN showed slower performance on large datasets  
4. Decision Tree provided clear decision rules  

## 9. Features
1. Interactive Streamlit interface  
2. Real-time prediction capability  
3. Model comparison and visualization  
4. User-friendly design  

## 10. Deployment
https://newsfakedetection.streamlit.app/

## 11. Tech Stack
1. Python  
2. Streamlit  
3. Scikit-learn  
4. Pandas  
5. NumPy  
6. Matplotlib  
7. Seaborn  

## 12. How to Run
1. Install dependencies:
   pip install -r requirements.txt  

2. Run the application:
   streamlit run fake_news_detection.ipynb  

## 13. Authors
1. Kanukuntla Shailaja  

SR University, Warangal  

## 14. My Contribution
1. Developed the complete machine learning pipeline  
2. Implemented multiple classification models  
3. Built the Streamlit web application  
4. Performed model evaluation and visualization  
5. Deployed the system for real-time use  

## 15. Conclusion
This project demonstrates how machine learning can be applied to detect fake news effectively and provide real-time insights through an interactive web application.
