# Sentiment Analysis using NLP

##  Project Overview
This project performs **Sentiment Analysis** on textual data using **Natural Language Processing (NLP)** techniques.  
The goal is to classify text into **positive or negative sentiment** using machine learning.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas, NumPy
- NLTK
- Scikit-learn
- Matplotlib, Seaborn

##  Dataset
The dataset consists of textual sentences/reviews labeled with sentiment values.
- `Train.csv` – Training data  
- `Valid.csv` – Validation data  
- `Test.csv` – Testing data  

##  Methodology
### 1. Data Preprocessing
- Converted text to lowercase
- Removed punctuation, numbers, and extra spaces
- Removed stopwords using NLTK

### 2. Feature Extraction
- Used **TF-IDF Vectorization** to convert text into numerical form

### 3. Model Building
- Implemented **Logistic Regression**
- Split data into training and testing sets

### 4. Model Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix

##  Results
The model achieved **high accuracy**, demonstrating effective sentiment classification on textual data.

##  Applications
- Product review analysis
- Social media sentiment analysis
- Customer feedback analysis

##  Conclusion
This project demonstrates how NLP and machine learning can be used to analyze sentiment in text data.  
It provides a strong foundation for advanced NLP applications.

