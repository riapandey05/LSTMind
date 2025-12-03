LSTMind – Next Word Predictor Using LSTM

Predict the next word like Shakespeare.

🧠 Overview

LSTMind is an AI-powered next-word prediction app built using LSTM (Long Short-Term Memory) neural networks.
The model is trained on Shakespeare’s Hamlet dataset to generate text in a similar style.
The project includes:

A clean Streamlit-based UI

A trained LSTM deep learning model

Real-time next-word prediction

Custom text continuation in Shakespearean style

🚀 Features

Next-Word Prediction: Suggests the most probable next word for a given input.

Text Generation: Continue text in Shakespeare’s tone and vocabulary.

Streamlit Deployment: Lightweight, fast, and interactive web UI.

Preprocessing Pipeline: Tokenization, sequencing, vocabulary creation, and padding.

Trained on Hamlet: Captures Elizabethan writing patterns.

🗂️ Project Structure
LSTMind/
│── data/
│   └── hamlet.txt
│── model/
│   └── lstm_nextword_model.h5
│── app.py
│── preprocess.py
│── train.py
│── README.md
│── requirements.txt

🔧 Tech Stack

Python

TensorFlow / Keras

NumPy, Pandas

NLTK / Tokenizer

Streamlit

Matplotlib (optional for training visualization)

🧪 Model Architecture

Embedding Layer

2-layer LSTM network

Dense Output Layer (Softmax)

Trained using:

Categorical crossentropy

Adam optimizer

Custom sequence generation pipeline

▶️ Run Locally
1. Clone the Repository
git clone https://github.com/your-username/LSTMind.git
cd LSTMind

2. Install Dependencies
pip install -r requirements.txt

3. Run Streamlit App
streamlit run app.py

🌐 Live Demo

If you deployed it, add the link here:

🔗 https://your-streamlit-app-url

📘 How It Works

Input a few words into the text box

LSTMind predicts the next word based on learned Shakespearean patterns

Auto-generate text sequence by clicking “Generate Text”

📊 Training Details

Dataset: Hamlet by William Shakespeare

Vocabulary Size: X words

Total Sequences: Y sequences

Training Epochs: Z epochs
(Fill these numbers if you want)

🛠️ Future Improvements

Add top-k and temperature-based sampling

Include more Shakespeare plays

Add multi-word prediction

Host backend with FastAPI for performance

✨ Author

Ria Pandey
AI & ML Enthusiast | B.Tech CSE
📍 VIT Bhopal
