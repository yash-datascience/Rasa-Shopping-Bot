# Rasa-Shopping-Bot

## Description

This is a demo project representing my work in Conversational AI during my 9 months internship at Innodatatics Inc. This is a shopping bot for smartphones and laptops. This chatbot was built over RASA framework which is an open source framework for Conversational AI assistance. This chatbot was trained using rasa nlu which is an inbuilt nlu pipeline inside rasa framework. The intents, entities, actions and stories are defined manually but are upgradable as the bot goes into production and collects more data.

## Initializing Bot

 * To initialize bot we have first create virtual enviornment using `python 3.6.9 version` and install `rasa 2.0.2 version` because all the files are written and coded according to these versions.
 * Use command `rasa train nlu` for training the intents and entities.
 * Use command `rasa train` to train a model using your NLU data and stories, saves trained model in ./models .
 * Use command `rasa shell` to load your trained model and lets you talk to your assistant on the command line.
