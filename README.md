# NLTK-PyTorch-chatbot initial setup

Clone repo
`
git clone 
cd NLTK-PyTorch_chatbot
`

Create virtual environment and install dependencies
`
python -m venv env
env\Scripts\activate
pip install flask torch torchvision nltk
`

Install nltk package
`
(venv) python
>>> import nltk
>>> nltk.download('punkt')
`

Modify intents.json with different intents and responses for your Chatbot

Run
`
python train.py
`

This will dump data.pth file. And then run the following command to test it in the console.
`
python chat.py
`

RUn the app.py script for demo.
