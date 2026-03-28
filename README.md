# Harf-level RNN (maktab)

This project demonstrates a simple character-level Recurrent Neural Network (RNN) built with PyTorch.

The model is trained on a single word: **"maktab"** and learns to predict the next character in the sequence.

---

## Project Goal

The goal is to teach the model character dependencies:

- m → a  
- a → k  
- k → t  
- t → a  
- a → b  

Input sequence: `makta`  
Target sequence: `aktab`

---

## Technologies Used

- Python
- PyTorch
- Jupyter Notebook

---

## Model Architecture

- `nn.RNN` layer
- `nn.Linear` layer
- CrossEntropyLoss
- Adam optimizer

---

## Training Settings

- Hidden size: 10  
- Learning rate: 0.02  
- Epochs: 200  

---

## Results

During training:
- Loss decreases over epochs  
- Model predictions improve gradually  

Final prediction should be close to:
