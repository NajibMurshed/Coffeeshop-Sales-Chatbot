# Coffeeshop-Sales-Chatbot
- This is a Chatbot that can interact with customers of a coffee shop. It is a relatively smart and simple chatbot that can greet customers, tell the menu and payment methods along with cracking some jokes.
- The chatbot is trained using a Feed Forward Neural net with 2 hidden layers.
- Prerequisites to start the project:
  1) Install Anaconda and Python 3
  2) Install Pytorch [https://pytorch.org]
  3) Install libraries: nltk, numpy and pandas
  4) Install nltk.tokenize.punkt through terminal: 
     python
     import nltk
     nltk.download('punkt')
  5) Install the virtualenv package: pip install virtualenv
  6) Create the virtual environment: virtualenv mypython
  7) Activate the virtual environment: 
    `Windows:`
     mypthon\Scripts\activate
    `MAC:`
     source mypython/bin/activate
     
  8) Insert the following commands in the virtual environment:
     python train.py
     python chat.py
     



