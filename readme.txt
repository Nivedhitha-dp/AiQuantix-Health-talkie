This is a Rasa Server that is to be instantiated/installed, thus:

Requirement are:

rasa==3.0.0
rasa-sdk==3.0.0
spacy==3.0.6
geopy

To run the program:
1. Train the model:  rasa train
2. rasa run -m models --enable-api --cors "*"
3. Run the action server: rasa run actions --cors "*"


Major Files descriptions:
1. index.html - The executable file
2. CSS and JS folder - for frontend of the chatbot and webpage
3. Data folder - For nlu, stories and rules, taht contains the intents
4. Action.py - Python programming for rasa server action
5. Models - The trained models
6. chats.csv - The storage of conversations
7. domain.yml - To indicate the response of chatbot - utter messages
