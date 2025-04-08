# Next Word Prediction Using LSTM-GRU

Devised a hybrid LSTM-GRU model to predict the next word in a sequence of text using deep learning. The model leverages the strengths of both Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) networks, which are well-suited for sequential and contextual data modeling tasks such as natural language processing.

---

## 🚀 Project Overview

This project demonstrates how deep learning can be applied to natural language understanding by building a model capable of predicting the next word based on a given input sequence. It uses a classical literary dataset to train and evaluate the model's performance.

---

## 🧠 Architecture

- **Model Type**: Hybrid LSTM-GRU Neural Network  
- **Layers**:
  - Embedding Layer
  - LSTM Layer
  - GRU Layer
  - Dense Output Layer with Softmax Activation

---

## 📁 Workflow

1. **📚 Data Collection**  
   - Dataset: Shakespeare's *Hamlet*  
   - Reason: Complex sentence structures and rich vocabulary are ideal for training NLP models.

2. **⚙️ Data Preprocessing**  
   - Tokenization and text-to-sequence conversion  
   - Padding sequences for uniform input shape  
   - Splitting into training and test sets  

3. **🏗️ Model Building**  
   - Constructed using TensorFlow/Keras  
   - Combines LSTM and GRU layers for better sequence learning  
   - Output layer predicts probability distribution over the vocabulary

4. **🎯 Training**  
   - Trained with categorical crossentropy loss  
   - Early stopping used to prevent overfitting based on validation loss

5. **🧪 Evaluation**  
   - Evaluated using example inputs  
   - Measures prediction accuracy and contextual understanding

6. **🌐 Deployment**  
   - Integrated into a web app using **Streamlit**  
   - Users can enter text and receive real-time next word predictions

---

## 📦 Tech Stack

- Python
- TensorFlow / Keras
- NLTK
- NumPy / Pandas
- Streamlit

