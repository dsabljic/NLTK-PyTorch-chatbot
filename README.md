# NLTK-PyTorch-chatbot initial setup

Clone repo
```bash
git clone https://github.com/dsabljic/NLTK-PyTorch-chatbot.git
cd NLTK-PyTorch_chatbot
```

Create virtual environment and install dependencies
```bash
python -m venv env
env\Scripts\activate
pip install flask torch torchvision nltk
```

Install nltk package
```bash
python
>>> import nltk
>>> nltk.download('punkt')
```

Modify intents.json with different intents and responses for your Chatbot

Run
```bash
python train.py
```

This will dump data.pth file. And then run the following command to test it in the console.
```bash
python chat.py
```

Run the app.py script for demo.
