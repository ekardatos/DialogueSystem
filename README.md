# DialogueSystem
This project demonstrates the creation of an intent classification model using Rasa to guide users through a sofa selection process. 
Rasa is an open-source machine learning framework (python) used to create conversational chatbots. It is used to automate the text and voice-based assistants.
This agent is text-based.

## About

Dialogue system built with Rasa, covering natural language understanding, generation, and conversation management.

## Project Structure
```
DialogueSystem/
├── nlu.yml                  # Training data — intents and entities
├── domain.yml               # Bot domain — intents, entities, responses, actions
├── stories.yml              # Conversation flow training stories
├── config.yml               # Rasa pipeline and policy configuration
├── actions.py               # Custom actions
├── bot_description.txt      # Bot description
├── sample_interactions.txt  # Example conversations
├── Rasa_actions.xlsx        # Actions reference sheet
├── Results/                 # Evaluation outputs and confusion matrices
├── TrainTest/               # Training and testing data splits
└── README.md
```
