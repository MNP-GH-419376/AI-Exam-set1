# 🚨 Tweet Urgency Detection

This project predicts whether a customer support tweet is **urgent** (needs a reply within 1 hour) or **non-urgent**.

We trained a machine learning model using the DistilBERT transformer (from Hugging Face) and built a simple Streamlit web app to interact with it.

---

## 📌 Features

- Input: A tweet message
- Output: Urgency prediction (Urgent / Non-Urgent) + confidence score
- Model: Fine-tuned DistilBERT on tweet data
- Interface: Simple web app built with Streamlit

---

## ▶️ How to Run

1. Make sure your model is saved in a folder named `tweet_urgency_model/`
2. Run the Streamlit app:

```bash
streamlit run app.py
