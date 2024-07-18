# Chat SoC - AI Powered Chatbot

Chat SoC is an AI-powered chatbot developed to interact with users through text input. It offers various functionalities such as text-to-image generation, text-to-audio conversion, image downloading from URLs, YouTube video downloading, and general conversational capabilities.

## Features

- **Text-to-Image Generation**: Enter an idea, and the chatbot generates an AI-powered image based on the input.
- **Text-to-Audio Conversion**: Converts text input into speech output.
- **Image Download from URL**: Downloads images from provided URLs.
- **YouTube Video Download**: Downloads videos from YouTube URLs.
- **AI Chat**: Engages in general conversation and provides responses based on the input.

## Setup

### Prerequisites

- Python 3.x installed
- Required Python packages: `numpy`, `pandas`, `matplotlib`, `scikit-learn`, `datetime`, `operator`, `pyttsx3`, `wikipedia`, `webbrowser`, `speech_recognition`, `python-dotenv`, `requests`, `pytube`, `opencv-python`, `pyzbar`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chat-soc.git
   cd chat-soc
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. **Login and Authentication**:
   - Run `main.py` to initiate the chatbot.
   - Provide your username and password for authentication.
   - Optionally, if you have a premium account (`owned` or `subscribed`), you can scan a SoC ID for verification.

2. **Interacting with Chat SoC**:
   - Enter commands such as `/text to image`, `/say this`, `/download image`, `/youtube video download`, or `/quit` to interact with different features of the chatbot.
   - For general conversation, simply enter your query or statement.

3. **Additional Notes**:
   - Maximum chat history is limited to 10 chats to optimize performance.
   - Ensure all dependencies are installed and configured correctly for smooth operation.


## License

This project is licensed under the MIT License.

---
