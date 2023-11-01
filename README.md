# Phase-5
This chatbot makes use of intent recognition and deep learning. A question that already has an answer in the database may be asked by the user. However, there are numerous ways to phrase the same question, and it is not feasible to hard-code every conceivable combination into the code. In order to solve this issue, we assign an intention to every response in our database. 'Intention' refers to the question's meaning. The identical question asked in different ways by the user will all be mapped to the same goal since they share the same overall meaning. After that, the matching response is given back.

eg. 'Hello' , 'Hi' , 'Nice to meet you' and 'Good morning' can all be mapped to the intention 'Greeting'. Then the answer for this intention is return, such as 'Nice to meet you too' or 'Hi'.

The model is currently trained on a small number of intents. It recognizes the intent of the user's query and gives the appropriate response.

The chat bot is in python. The python script uses a model which has been trained on many intents. Using this model, it predicts the intent of the user entered text. For each intent, the chatbot chooses the best reply and interacts with the user.


**SETUP:**
Implement the code using Jupyter Notebook or Google Colaboratory.
Requirements: python3.5 spacy 2.0.5 keras 2.1.2 tensorflow 1.4.1 sys numpy scikit-learn scipy cython nltk
Libraries required tensorflow, keras, pandas, json, nltk, pickle.
After installing spacy you need to get the spacy model called en. Do:
python -m spacy download en
If the library is not available, then install the library using the command pip install library_name


Adding more intents:
More intents can be used by adding them to the intent.json file attached. The intent should be addd in the format tags, patterns and responses where tag represents the type of input such as greetings, goodbyes etc. Pattern represents the set of statements that contains different ways in which the user can pose a question to the chatbot. Response represents the set of all statements from which the chatbot chooses the reply to be given to the user.



  
