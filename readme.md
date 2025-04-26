# 🧠 SimpleRNN

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
[![Python](https://img.shields.io/badge/python-3.7%2B-blue.svg)](https://www.python.org/)

A simple Recurrent Neural Network (RNN) built using **Keras** to perform **sentiment analysis** on the IMDB movie reviews dataset.

---

## 📦 Setup Locally

Get started in minutes:

### 1. Clone the repository

```bash
git clone https://github.com/coder-tejas/SimpleRNN.git
cd SimpleRNN
```

### 2. (Optional) Set up a virtual environment

```bash
# Create virtual environment
python -m venv venv

# Activate
# On Windows
venv\Scripts\activate

# On Linux/Mac
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the project

Launch Jupyter Notebooks:

```bash
jupyter notebook
```

Open and run:

- `RNN.ipynb`
- `embedding.ipynb`
- `simplernn.ipynb`
- `prediction.ipynb`

Or run the standalone Python script:

```bash
python main.py
```

(⚡ Make sure `simple_rnn_imdb.h5` model file is present if you want to load a pretrained model.)

---

## 🛠️ Project Structure

```bash
SimpleRNN/
├── RNN.ipynb            # Introduction to RNNs
├── embedding.ipynb      # Word embedding demo
├── simplernn.ipynb      # Building/training SimpleRNN
├── prediction.ipynb     # Predictions using the model
├── main.py              # Script version
├── simple_rnn_imdb.h5   # Pretrained model file
├── requirements.txt     # List of dependencies
└── README.md            # (This file!)
```

---

## 🧰 Tech Stack

- Python 3.7+
- TensorFlow & Keras
- NumPy
- Jupyter Notebook

---

## 🚀 Future Improvements

- Add LSTM / GRU models for better performance
- Explore attention mechanisms
- Fine-tune with custom datasets

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## ✨ Acknowledgments

Built with ❤️ by [coder-tejas](https://github.com/coder-tejas)