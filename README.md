## Next Word Prediction Using LSTM and GRU

### Project Overview

This project aims to develop a deep learning model for predicting the next word in a given sequence of words. The model is built using Long Short-Term Memory (LSTM) networks, which are well-suited for sequence prediction tasks. The project follows these steps:

### 1. Data Collection
We use the text of Shakespeare's *Hamlet* as our dataset. This rich, complex text provides a good challenge for our model.

### 2. Data Preprocessing
- Tokenization of text data
- Conversion into sequences
- Padding sequences to ensure uniform input lengths
- Splitting data into training and testing sets

### 3. Model Building
The model consists of:
- An embedding layer
- Two LSTM layers
- A dense output layer with a softmax activation function to predict the probability of the next word

### 4. Model Training
- Training the model using the prepared sequences
- Implementing early stopping to prevent overfitting
- Monitoring validation loss to stop training when no further improvement is observed

### 5. Model Evaluation
- Evaluating the model's performance using example sentences
- Testing the model’s ability to predict the next word accurately

### 6. Deployment
- A Streamlit web application is developed
- Allows users to input a sequence of words and receive the predicted next word in real-time


