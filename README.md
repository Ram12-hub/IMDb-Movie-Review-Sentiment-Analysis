# IMDb-Movie-Review-Sentiment-Analysis
Sentiment analysis and news classification using NLP and ML models (Logistic Regression, SVC, Random Forest). Achieved 89% accuracy in sentiment analysis and 78% in news classification. Used TF-IDF, tokenization, and lemmatization for preprocessing.

## Sentiment Analysis and News Article Classification using NLP & ML
This project applies Natural Language Processing (NLP) and Machine Learning techniques to analyze text data and make accurate predictions.

 Project Overview
# 1. IMDb Movie Review Sentiment Analysis
Cleaned and preprocessed text data using tokenization, stopword removal, and lemmatization.
Converted text to numerical form using TF-IDF vectorization.

### Data preprocessing code glimps
![image](https://github.com/user-attachments/assets/96ca7130-6b6e-4ccd-b0a6-02793ba8c583)
### applying lemmatization
![image](https://github.com/user-attachments/assets/026b533e-6c76-4f22-8950-c8972001dda7)
### converting Categorical columns into numerical columns 
![image](https://github.com/user-attachments/assets/238738c5-20e7-4f51-bad5-7a87539f68ff)
### Building and evaluating through different models
![image](https://github.com/user-attachments/assets/f8a4a748-9137-45e0-bc4f-f44c03ded045)
![image](https://github.com/user-attachments/assets/a844117f-fdfb-4487-9998-68ccce33f02e)
![image](https://github.com/user-attachments/assets/bb263930-52eb-48ac-aede-212be2919df3)
![image](https://github.com/user-attachments/assets/7fc27025-f3b5-45d6-8f1d-356211671977)

Built and tested models:
>Logistic Regression – 89% accuracy 
> Linear SVC – 89% accuracy
> Random Forest – 85% accuracy
> Decision Tree – 73% accuracy 
Conclusion: SVC and Logistic Regression were the most effective models.

# 2. News Article Classification
Preprocessed news articles by cleaning and tokenizing text.
Applied TF-IDF vectorization to convert text into numerical format.
Built and tested models:
> Logistic Regression – 76% accuracy
> SVC – 78% accuracy
> Random Forest – 69% accuracy
Conclusion: SVC was the most accurate model for classification.

**Tech Stack**
Python
Pandas, NumPy
Scikit-Learn
TF-IDF Vectorization
Seaborn, Matplotlib

**Key Achievements**
✔ High accuracy in sentiment analysis using SVC and Logistic Regression.
✔ Effective classification of news articles using SVC.
✔ Clean and scalable preprocessing pipeline for NLP tasks.
