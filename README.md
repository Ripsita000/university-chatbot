# 🎓 University Chatbot using NLTK & TensorFlow

A simple NLP-based chatbot that helps answer university-related questions like admissions, fees, campus, etc.

---

## 🔧 Features

- Intent classification using Deep Learning
- Preprocessing with NLTK (tokenizing, lemmatizing)
- Trained on custom `intents.json` data
- Uses bag-of-words model

---

## 🧠 Tech Used

- Python
- NLTK
- TensorFlow/Keras
- NumPy

---

## 📂 Project Structure

university-chatbot/ │ ├── data/ │ └── intents.json │ ├── model/ │ ├── model.h5 │ ├── words.pkl │ └── classes.pkl │ ├── chatbot.py ├── requirements.txt ├── README.md ├── .gitignore

---

## 🚀 How to Run

1. Clone the repo  
```bash
git clone https://github.com/Ripsita000/university-chatbot.git
cd university-chatbot
**Install dependencies**
pip install -r requirements.txt
python chatbot.py


💬 Example Interaction
You: hello
Bot: Hello! How can I assist you?

You: how do I apply?
Bot: You can apply through our admission portal. Need help with that?


