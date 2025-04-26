🧠 SimpleRNN
A minimalistic project showcasing how to build a Simple Recurrent Neural Network (RNN) using Keras for Sentiment Analysis on the IMDB dataset.

🚀 Project Setup (Local Installation)
Follow these quick steps to get started locally:

1. Clone the Repo
bash
Copy
Edit
git clone https://github.com/coder-tejas/SimpleRNN.git
cd SimpleRNN
2. (Optional) Create a Virtual Environment
Highly recommended to avoid messing up your global Python setup:

bash
Copy
Edit
# Create a virtual environment
python -m venv venv

# Activate it
# For Linux/MacOS
source venv/bin/activate

# For Windows
venv\Scripts\activate
3. Install Required Packages
bash
Copy
Edit
pip install -r requirements.txt
This will install packages like TensorFlow, Keras, and other essentials.

4. Run the Notebooks 📓
Fire up Jupyter:

bash
Copy
Edit
jupyter notebook
Then open any of the following notebooks:

RNN.ipynb

embedding.ipynb

simplernn.ipynb

prediction.ipynb

5. Alternatively, Run the Python Script 🖥️
If you want to directly execute the main script:

bash
Copy
Edit
python main.py
Make sure simple_rnn_imdb.h5 (the saved model) is present if the script depends on a pre-trained model!

📂 Project Structure
plaintext
Copy
Edit
SimpleRNN/
├── RNN.ipynb            # Basic RNN explanation and setup
├── embedding.ipynb      # Word embedding walkthrough
├── simplernn.ipynb      # Building and training a SimpleRNN
├── prediction.ipynb     # Prediction and evaluation
├── main.py              # Python script for quick runs
├── simple_rnn_imdb.h5   # Saved trained model
├── requirements.txt     # Project dependencies
└── README.md            # You are here!
🧩 Tech Stack
Python 3.x

TensorFlow + Keras

NumPy

Jupyter Notebook

✨ Future Scope
Add LSTM/GRU models for better handling of long-term dependencies

Implement attention mechanisms

Fine-tune on custom datasets beyond IMDB

🛡️ License
This project is open-source and available under the MIT License.

📣 Shoutout
Built with ❤️ by coder-tejas