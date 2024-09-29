# Mental Health Check-In Chatbot

## Overview

The *Mental Health Check-In Chatbot* is designed to assist users in monitoring their mental well-being. It offers personalized responses based on the user's emotional input, and provides access to crisis support when needed. The chatbot is powered by *Natural Language Processing (NLP)* techniques to help users express their emotions, receive relevant feedback, and track their emotional health over time.

## Features

- *Emotion Detection*: Analyze user input to detect emotions such as happiness, sadness, anxiety, and stress using NLP.
- *Daily Mental Health Check-In*: Allows users to check in daily and track their emotional health.
- *Personalized Feedback*: Provides tailored suggestions and advice based on user input.
- *Crisis Support*: Connects users to professional resources and helplines if needed.
- *Data Privacy*: Ensures user interaction data is handled privately, with an option for anonymous storage.

## Technologies Used


- *NLP Libraries*: For analyzing user input and detecting emotions.
  - *TextBlob* or *spaCy*: Used for basic sentiment analysis and emotion recognition.
  - *Hugging Face Transformers* (optional): For more advanced NLP models.
- *Flask* (or *FastAPI*): A lightweight framework used for creating the web interface to interact with the chatbot.
- *HTML/CSS/JavaScript*: Frontend for user interaction.
- *Dialogflow* (optional): For advanced conversational chatbot features.

## Setup and Installation

Follow these steps to set up and run the chatbot locally:


### Installation

1. *Clone the repository*:

    bash
    git clone https://github.com/gowthami9821/Mental_Health-Checkin-Chatbot.git
    cd mental-health-check-in-chatbot
    

2. *Create a virtual environment* (optional but recommended):

    bash
    python3 -m venv venv
    source venv/bin/activate
    

3. *Install the required dependencies*:

    bash
    pip install -r requirements.txt
    

4. *Run the application*:

    bash
    python app.py
    

5. *Access the chatbot*:
    - Open your browser and go to http://localhost:5000 to interact with the chatbot.

## How It Works

1. *User Input*:
   - Users interact with the chatbot by providing their current emotional state or answering mood-related questions.

2. *Emotion Detection*:
   - The chatbot uses *NLP* to analyze the user's input and classify it into emotions such as happy, sad, stressed, or anxious.

3. *Response Generation*:
   - Based on the user's detected emotion, the chatbot provides appropriate responses. For example:
     - If the user is happy, the chatbot acknowledges the positive emotion.
     - If the user is sad or stressed, the chatbot offers advice, such as relaxation exercises or self-care tips.

4. *Crisis Support*:
   - When the chatbot detects distress, it recommends contacting mental health professionals or helplines.

5. *Web Interface*:
   - The chatbot can be accessed via a web interface using *Flask* (or *FastAPI*), which allows users to interact with the chatbot in real-time.

### Code Structure

- app.py: Contains the main application code to run the chatbot using Flask.
- chatbot.py: Contains the chatbot logic, including emotion detection and response generation.
- nlp_module.py: Handles emotion analysis using an NLP library (e.g., TextBlob or spaCy).
- templates/: Contains HTML templates for rendering the chatbot web interface.

