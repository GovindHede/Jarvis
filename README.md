# JARVIS AI Assistant
![developer](https://img.shields.io/badge/Developed%20By%20%3A-Govind%20&__Tejas-red)

![Jarvis Logo](Graphics/Jarvis.gif)

JARVIS is an advanced AI-powered virtual assistant that combines speech recognition, natural language processing, and automation to simplify everyday tasks. This project is built using Python and leverages various APIs and libraries to create a robust and interactive experience.

---

## Features

- **Voice Interaction**: Speak to JARVIS and receive intelligent responses using Speech-to-Text and Text-to-Speech modules.
- **Chatbot Functionality**: Engage in meaningful conversations powered by a custom chatbot.
- **Image Generation**: Create AI-generated images with a single command.
- **Automation**: Automate tasks seamlessly.
- **Real-Time Search**: Get instant answers using the real-time search engine integration.
- **Graphical User Interface**: User-friendly GUI for enhanced interaction.
- **Customizable**: Modify responses, graphics, and more to suit your preferences.

---

## Project Structure

```plaintext
JARVIS
|
|-- Backend
|   |-- Automation.py          # Handles automated tasks
|   |-- Chatbot.py             # Chatbot logic and interactions
|   |-- ImageGeneration.py     # AI-based image generation module
|   |-- Model.py               # Core AI model logic
|   |-- RealtimeSearchEngine.py # Enables real-time search capabilities
|   |-- SpeechToText.py        # Converts speech to text
|   |-- TextToSpeech.py        # Converts text to speech
|
|-- Data
|   |-- ChatLog.json           # Stores chatbot conversation logs
|   |-- speech.mp3             # Audio output file
|   |-- Voice.html             # HTML file for voice processing
|
|-- Files
|   |-- Database.data          # Database for storing user data
|   |-- ImageGeneration.data   # Data for image generation
|   |-- Mic.data               # Microphone data handler
|   |-- Responses.data         # Customizable responses
|   |-- Status.data            # Stores status updates
|
|-- Graphics
|   |-- Chats.png              # Graphics for chat section
|   |-- Close.png              # Close button icon
|   |-- Home.png               # Home button icon
|   |-- Jarvis.gif             # Animated JARVIS logo
|   |-- Maximize.png           # Maximize button icon
|   |-- Mic_on.png             # Microphone on icon
|   |-- Mic_off.png            # Microphone off icon
|   |-- Minimize2.png          # Minimize button icon
|   |-- Settings.png           # Settings button icon
|
|-- GUI.py                     # Code for the graphical user interface
|-- Main.py                    # Main script to run JARVIS
|-- Requirements.txt           # Required Python libraries
|-- .env                       # Environment variables
|
|-- venv                       # Virtual environment directory
```

---

## Installation

### Prerequisites

- Python 3.10.10
- pip (Python package manager)
- Virtual environment setup (optional but recommended)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/JARVIS.git
   ```

2. Navigate to the project directory:
   ```bash
   cd JARVIS
   ```

3. Create a virtual environment (optional):
   ```bash
   python -m venv venv
   source venv/bin/activate    # On Windows: venv\Scripts\activate
   ```

4. Install the required libraries:
   ```bash
   pip install -r Requirements.txt
   ```

5. Configure the `.env` file with your API keys and other sensitive data.

6. Run the application:
   ```bash
   python Main.py
   ```

---

## Usage

- Launch the application by running the `Main.py` script.
- Interact with JARVIS via voice commands or the GUI interface.
- Use the settings to customize responses, audio output, and more.

---

## Screenshots

### Home Screen


### Chat Interface
![Chat Interface](Graphics/Chats.png)



---

## Contributions

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- [Python](https://www.python.org/)
- [Cohere](https://cohere.com/)
- [HuggingFace](https://huggingface.co/)
- [Groq](https://gorq.dev//) for APIs

---

Give JARVIS a try and experience the power of AI in your hands!

