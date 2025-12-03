
# 🚀 **LSTMind — Next Word Predictor Powered by LSTM**

## 🧠 **Overview**

**LSTMind** is a deep-learning based **Next Word Prediction** system trained on **Shakespeare’s *Hamlet***.
Using an **LSTM neural network**, it learns Elizabethan writing patterns and predicts the most likely next word for any input text.
The project includes an elegant **Streamlit interface** for real-time text generation.

---

# ✨ **Features**

* 🔤 **Next Word Prediction** using LSTM
* 📜 **Shakespeare-style text generation**
* 🎭 Trained on *Hamlet*
* ⚡ **Streamlit Deployment** with interactive UI
* 🔧 Custom NLP preprocessing & tokenization
* 📈 Easily extendable for more datasets

---

# 📂 **Project Structure**

```
LSTMind/
│── data/
│   └── hamlet.txt
│── model/
│   ├── lstm_nextword_model.h5
│   ├── tokenizer.pkl
│   └── metadata.json
│── train.py
│── preprocess.py
│── app.py
│── requirements.txt
│── README.md
```

---

# 🛠️ **Tech Stack**

* **Python 3.x**
* **TensorFlow / Keras**
* **NumPy, Pandas**
* **Tokenizer (Keras)**
* **Streamlit**

---

# 🧵 **Model Architecture**

* **Embedding Layer**
* **2-Layer LSTM Network**
* **Dense Output Softmax Layer**
* Optimizer: **Adam**
* Loss: **Categorical Crossentropy**

---

# ▶️ **How to Run the Project**

### **1. Clone the Repository**

```bash
git clone https://github.com/your-username/LSTMind.git
cd LSTMind
```

### **2. Install Dependencies**

```bash
pip install -r requirements.txt
```

### **3. Run Streamlit App**

```bash
streamlit run app.py
```

---

# 🌐 **Live Demo (Optional)**

Add your Streamlit link here:

```
🔗 lstmind.streamlit.app/
```

---

# 📘 **How It Works**

1. User enters a few words
2. Model processes input sequence
3. LSTM predicts the most probable next word
4. Optionally generates long Shakespeare-style text

---

# 📊 **Training Summary**

* Dataset: **Hamlet — William Shakespeare**
* Vocabulary Size: *add your number here*
* Training Sequences: *add number*
* Epochs: *add number*
  (*Optional to fill in later*)

---

# 🛣️ **Future Enhancements**

* Add **Top-k Sampling**
* Add **Temperature Control**
* Add **Multiple Shakespeare Plays**
* Deploy backend API using **FastAPI**
* Add **multi-word prediction**

---

# 👩‍💻 **Author**

**Ria Pandey**
AI/ML Enthusiast | B.Tech CSE
📍 VIT Bhopal

