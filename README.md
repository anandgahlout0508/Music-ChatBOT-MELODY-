# MELODY - Music Chatbot

## Description
MELODY is an AI-powered music chatbot written in Python. The chatbot aims to engage with users, providing information about music, the benefits of listening to music, and suggesting songs based on different moods. MELODY can understand spoken language using speech recognition and respond with synthesized speech using text-to-speech capabilities.

## Features
1. Introduction and interaction with the user
2. Answering questions about music and its benefits
3. Providing song recommendations based on user preferences
4. Continuously listening for user inputs until the user chooses to leave

## Prerequisites
Before running the music chatbot, you need to have the following installed:

Python (3.6 or above)
Required Python packages (install using pip install pyttsx3 speech_recognition)

## Usage
1. Clone this repository to your local machine using the following command:

git clone https://github.com/anandgahlout0508/Ai-based-translator.git

2. Navigate to the project directory.
3. Run the music_chatbot.py script:

python music_chatbot.py

a. The chatbot will greet you and ask for your name. It will then introduce itself and describe its capabilities.
b. The chatbot will listen for your response using your microphone. You can speak to the chatbot and ask questions or request song recommendations.
c. To end the conversation with the chatbot, simply say "leave," and the chatbot will bid you farewell.

## Available Commands

### What is music?:
The chatbot will explain what music is and its cultural significance.

### What are the benefits of listening to music?:
The chatbot will list the benefits of listening to music, such as elevating mood, reducing stress, stimulating memories, and enhancing learning.

### I would like to listen to music: 
The chatbot will prompt you to specify the type of songs you'd like to listen to (e.g., sad songs, inspirational songs, romantic songs, workout songs, or sufi songs).

### Leave: 
To end the conversation with the chatbot and exit the program.

## How it Works
The music chatbot leverages the pyttsx3 library for text-to-speech functionality, allowing it to communicate with the user using synthesized speech. For speech recognition, the chatbot uses the speech_recognition library, which enables it to understand and process the user's spoken inputs. The chatbot then responds based on the recognized commands and provides appropriate answers or song recommendations.

## Contributing
Contributions to this project are welcome! If you find any issues or want to enhance the functionality, please feel free to create a pull request.

## Acknowledgments
We would like to thank the developers and contributors to this project. Additionally, we appreciate the open-source community for providing valuable resources and tools that make this chatbot possible.





