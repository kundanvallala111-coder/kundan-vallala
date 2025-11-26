Mythology Chatbot — NLP Project:
This project is a simple and interactive Mythology Chatbot built using Natural Language Processing (NLP).
It can answer questions related to different mythologies such as Greek, Norse, Roman, Indian, and more.
The goal of this project was to understand how NLP works and how chatbots can be built using machine learning.



About the Project:
The Mythology Chatbot reads what the user types, tries to understand the meaning using NLP techniques, and then replies with a mythology-related answer.
It was developed as part of my NLP (Natural Language Processing) coursework and helped me learn:
How text is processed in machines
How chatbots classify user messages
How machine learning models respond to queries
This chatbot is fully customizable — new mythological characters or stories can be added anytime.

Project Goals:
The main objectives of this project were:
To apply NLP concepts in a practical project
To build a simple chatbot using machine learning
To understand intent classification
To create a mythology-based Q&A system
To gain hands-on experience with real text processing

Tools & Technologies Used:
Python
NLTK for text cleaning and preprocessing
TensorFlow / Keras for training the model
NumPy
JSON for storing intents and responses
Google Colab for development and training

Project Structure
Mythology-Chatbot/
│
├── mythology_intents.json     # Dataset of questions and responses
├── model.h5                   # Trained ML model
├── words.pkl                  # Tokenized words from the dataset
├── classes.pkl                # Categories/intents for classification
├── chatbot.ipynb              # Main Colab notebook
└── README.md                  # Documentation file



How the Chatbot Works:
Here’s a simple explanation of the process:
1. Understanding the Dataset
All questions and answers are stored in a single JSON file with categories like:
Greeting
Zeus
Thor
Krishna
And many more (customizable)
2. Preprocessing
Before training, all the text is cleaned using:
Tokenization (splitting sentences into words)
Lemmatization (converting words to base form)
Bag-of-Words vectorization
3. Training the Model
A small neural network learns patterns from the dataset and understands what the user is asking.
4. Generating Responses
When the user types something:
The chatbot predicts the intent
Picks a response from the dataset
Returns it in a conversational way


Features of the Chatbot:
Answers basic mythology questions
Supports multiple mythologies
Lightweight and fast
Easy to modify by editing one JSON file
Works completely offline after training
Beginner-friendly NLP project


How to Use the Project:
Open the notebook in Google Colab
Load the JSON dataset
Train the model or load the saved model.h5 file
Run the chatbot cell
Start chatting with your bot through the input box

Future Improvements:
Some features that can be added in the future:
More mythology categories and characters
Voice-based interaction
Web or mobile app interface
More advanced models like LSTM or BERT
Context-based responses


Developed By
VALLALA SAI KUNDAN RAJU
GADIPARTHI DAYA SAGAR
DAGGU RISHITHA RAO
MARRI MITHUL REDDY
MAYALURI VIVEKANANDA REDDY
