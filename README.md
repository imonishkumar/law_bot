# Lawbot Using NLP
## Project Overview:

This Python project implements a Law Bot using a simple neural network for natural language processing. The bot is designed to understand user inputs related to legal queries and provide appropriate responses. 

## The project consists of several files:

    train.py: Used to train the neural network model based on the data in intents.json and saves the model information in data.pth.
    
    model.py: Defines the structure of the linear neural network used for processing user inputs.
    
    nltk_utils.py: Provides utility functions for tokenization, stemming, and creating a bag of words from text data.
    
    chat.py: Accepts user input and utilizes the trained model to generate relevant responses.
    
    intents.json: Stores data in the form of key : value pairs.

## Project Files:

1. train.py
    This file is responsible for training the neural network based on the data provided in the intents.json file. The trained model information is then stored in the data.pth file for later use.

2. model.py
    Defines the architecture of the neural network used for the Law Bot. The model is a simple linear neural network suitable for text classification tasks.

3. nltk_utils.py
    Contains utility functions for natural language processing tasks, including tokenization, stemming, and creating a bag of words.

4. chat.py
    Handles the interaction with the user. Takes user input, processes it using the trained model, and provides appropriate responses.

## Data Storage:

    intents.json: Contains the training data for the Law Bot in JSON format. Each intent includes a list of patterns (user inputs) and possible responses.

    data.pth: Stores the trained neural network model's information. This file is generated after running train.py and is used by chat.py to make predictions.

## Getting Started:

1. Install dependencies:

    pip install -r requirements

2. Train the model:

    python train.py

4. Interact with the Law Bot:

    python chat.py

## Customization:

Feel free to customize the intents.json file to add or modify intents and responses based on your specific use case. Adjust the neural network architecture in model.py if necessary.

## Requirements:

Ensure that you have Python installed (version 3.x) and install the required dependencies using:

    pip install -r requirements

## Acknowledgments:

This project is built using Python, NLTK for natural language processing, and PyTorch for creating and training the neural network model.
