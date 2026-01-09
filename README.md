# Fake News Detection System

This project is a Fake News Detection System developed as part of an
Undergraduate / Top-Up Computing Project.

The system uses a Next.js frontend for user interaction and a Python-based
machine learning backend to classify news as Fake or Real.

---

## Project Overview
Fake news has become a major challenge in digital media. This project aims to
automatically detect fake news articles using machine learning techniques
applied to textual data.

Users can enter news content through a web interface, and the system predicts
whether the news is Real or Fake.

---

## Technologies Used

### Frontend
- Next.js
- JavaScript
- React
- HTML / CSS

### Backend
- Python
- Flask (REST API)

### Machine Learning
- Logistic Regression
- Random Forest
- Natural Language Processing (NLP)

### Libraries & Tools
- scikit-learn
- pandas
- numpy
- nltk
- joblib / pickle

---

## System Architecture
1. User inputs news text via the Next.js interface.
2. The frontend sends the input to the backend API.
3. Text preprocessing is applied using NLP techniques.
4. The trained machine learning model classifies the news.
5. The prediction result (Real or Fake) is returned to the frontend.

---

## Dataset
The dataset used in this project is the **Real vs Fake News Dataset** obtained
from **Kaggle**.

The dataset contains labeled news articles categorized as *Real* or *Fake* and
is commonly used for fake news detection research and experimentation.

Dataset Source: Kaggle – Real vs Fake News Dataset

---

## How to Run the Project Locally

### Backend Setup
```bash
cd backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python app.py

