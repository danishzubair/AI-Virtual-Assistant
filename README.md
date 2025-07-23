AI Virtual Assistant
Overview

The AI Virtual Assistant is a Python-based voice-controlled application designed to help children and adults overcome shyness in speaking and practice communication skills in a supportive environment. It also functions as a personal assistant, similar to Alexa, enabling users to perform tasks such as playing music, searching the web, checking the time, writing notes, and more. The assistant, named "Tom," fosters a friendly interaction by responding to personal questions and encouraging learning, making it ideal for users who lack a conversation partner or need assistance with daily tasks.

The system uses speech recognition to process voice commands and text-to-speech to provide spoken responses, creating an engaging and interactive experience. Key features include playing YouTube videos, retrieving Wikipedia summaries, telling jokes, and responding to conversational prompts with encouraging and friendly dialogue.

Project Description

The AI Virtual Assistant aims to:





Support Communication Practice: Help users, especially those with shyness, practice speaking through friendly and encouraging interactions.



Act as a Personal Assistant: Perform tasks like playing music, checking the time, searching the web, and telling jokes, inspired by assistants like Alexa.



Promote Learning: Encourage users to prioritize learning over entertainment, with responses that motivate educational growth.

The assistant responds to a variety of voice commands, such as playing songs, searching for information, answering personal questions (e.g., "Are you my friend?"), and providing motivational feedback. It uses libraries like speech_recognition, pyttsx3, pywhatkit, wikipedia, and pyjokes to enable its functionalities.

Features





Speech Recognition: Listens to voice commands using Google’s speech recognition API.



Text-to-Speech: Provides spoken responses with a customizable voice (set to a female voice by default).



Music Playback: Plays songs or videos on YouTube via pywhatkit.



Web Search: Retrieves and speaks Wikipedia summaries for requested topics.



Conversational Responses: Responds to personal questions (e.g., "Do you love me?", "Are you my friend?") with friendly, encouraging replies.



Time Queries: Provides the current time in a spoken format.



Joke Telling: Shares jokes using the pyjokes library.



Motivational Dialogue: Encourages learning and positive engagement, especially for shy users.

Technologies Used





Python 3.x: Core programming language.



speech_recognition: For capturing and processing voice input via Google Speech Recognition.



pyttsx3: For text-to-speech functionality.



pywhatkit: For playing YouTube videos and other web-based tasks.



wikipedia: For retrieving and summarizing web content.



pyjokes: For generating jokes.



datetime: For handling time-related queries.

Installation





Clone the Repository:

git clone https://github.com/danishzubair/ai-virtual-assistant.git



Navigate to the Project Directory:

cd ai-virtual-assistant



Set Up a Virtual Environment (recommended):

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate



Install Dependencies:

pip install speechrecognition pyttsx3 pywhatkit wikipedia pyjokes





Note: On Windows, you may need to install pywin32 for pyttsx3:

pip install pywin32



Ensure espeak or a compatible TTS engine is installed on Linux/macOS for pyttsx3.



Set Up Microphone:





Ensure a working microphone is connected and configured.



Run python -m speech_recognition to test microphone setup and adjust device_index in the code if needed (default is 0).

Usage





Run the Application:

python assistant.py



Interact with the Assistant:





Say “Alexa” followed by a command (e.g., “Alexa, play Happy by Pharrell Williams”).



Example commands:





Music: “Play [song name]” (e.g., “Play Happy”).



Time: “What’s the time?”.



Search: “Search [topic]” (e.g., “Search Python programming”).



Joke: “Tell me a joke”.



Conversational: “Are you my friend?”, “Do you love me?”, “Let’s have a game”, “How old are you?”.



Exit: “Bye” to close the assistant.



Practice Speaking:





Engage in conversations to build confidence, especially for shy users. The assistant responds positively to encourage speaking.



Troubleshooting:





If the assistant doesn’t hear you, ensure the microphone is working and adjust device_index in the code.



For errors with speech recognition, check your internet connection (Google API requires internet).

Repository Structure

ai-virtual-assistant/
├── assistant.py       # Main Python script for the AI Virtual Assistant
└── README.md         # This file

Contributing

This project is a personal portfolio piece. Contributions are not expected, but feedback is welcome. Contact me at danish347291@gmail.com or via GitHub Issues.

License

This project is for demonstration purposes and not licensed for public use. All rights reserved by Danish Zubair.

Contact





Email: danish347291@gmail.com



Phone: +44 (0) 7405 877 612



GitHub: danishzubair



LinkedIn: Your LinkedIn Profile (Update with your actual profile)



Portfolio: danishzubair.github.io



Built by Danish Zubair, Software Engineering Student at University of Bradford, to support communication practice and personal assistance.
