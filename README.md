# Maya - A Virtual Assistant

**Maya** is a Python-based virtual assistant that can perform various tasks such as opening websites, fetching news headlines, and interacting with users using AI responses. Maya also supports voice-based interaction.

## Features

- **Voice Commands**: Maya listens and processes voice commands using speech recognition.
- **AI-Powered Responses**: Uses OpenAI's API for generating intelligent responses.
- **Web Access**: Open popular websites like Google, YouTube, Facebook, and Instagram via commands.
- **Music Playback**: Play songs from a predefined music library.
- **News Headlines**: Fetch and read out the latest news using NewsAPI.

## Prerequisites

Ensure you have the following installed:

1. Python 3.x
2. Required libraries (see below)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/maya-virtual-assistant.git
   cd maya-virtual-assistant
2. Install dependencies:
   pip install speechrecognition webbrowser pyttsx3 requests gtts pygame openai
   
3. Add your API keys
   NewsAPI: Replace newsapi with your NewsAPI key.
   OpenAI API: Replace the api_key in the ai_process function with your OpenAI API key.
   
## How to Run

1. Run the script:
   python maya.py
   
2. Speak the wake word: Maya.
   Once Maya responds, you can give your command.

## Available Commands

### General Commands
   "Open Google" - Opens Google in your default browser.
   "Open YouTube" - Opens YouTube.
   "Open Facebook" - Opens Facebook.
   "Open Instagram" - Opens Instagram.
   
### Music Commands
   "Play [song name]" - Plays a song from your predefined music library.
   
### News
   "News" - Reads out the latest news headlines.

### AI Assistance
   Any other commands are processed through OpenAI for a response.
   
## Configuration
   Music Library: Define a dictionary musicLibrary with song names as keys and URLs as values in a musicLibrary.py file.
   API Keys: Replace placeholders for API keys in the script.
   
### Example

   1. Wake up the assistant by saying:
      Maya
   2. Give a command, e.g.:
      Play Despacito
      Maya will fetch the song link from the library and play it.
   3. Or ask for news:
      News
      Maya will fetch the latest news and read out the headlines.

## Limitations
   Requires a stable internet connection for OpenAI API and NewsAPI.
   Command recognition may vary depending on microphone quality and noise.
   
## Contributing
   Feel free to fork this repository and contribute to the project! Pull requests are welcome for enhancements and bug fixes.

## Author
   Vikas Soan
