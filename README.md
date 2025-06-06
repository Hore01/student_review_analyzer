# student_review_analyzer
# Course Review Analyzer

This is a **Streamlit app** that allows students to input their course reviews and automatically analyzes:

- Sentiment (Positive, Negative, Neutral)
- Topics using a trained LDA topic model
- Confidence levels for topic prediction

---

## Features

- Real-time sentiment analysis with VADER
- Topic classification with pre-trained LDA model
- Saves each review to a CSV log
- Simple interface for student feedback

---

##  How to Run the App Locally

### Step 1: Download the Files

Make sure you have the following files in the same folder:
- app.py 
- lda_topic_model.pkl
- lda_vectorizer.pkl
- requirements.txt

### Step 2: Install Streamlit and Dependencies

Open your terminal or command prompt and run:

```bash
pip install -r requirements.txt

### Step 3: Launch the app
streamlit run app.py


