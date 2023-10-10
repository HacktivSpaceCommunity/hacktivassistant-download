# HacktivAssistant

## Overview

HacktivAssistant is a Python-powered desktop assistant that provides voice-controlled interactions and various functionalities, including web browsing, music playback, and AI-driven chatbot conversations. It leverages SpeechRecognition for voice input and integrates with OpenAI's GPT-3.5 Turbo model for natural language processing.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [License](#license)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/HacktivSpaceCommunity/hacktivAssistant-download.git
   ```

2. Navigate to the project directory:

   ```bash
   cd HacktivAssistant
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Configure your OpenAI API key in `config.py`:

   ```python
   # config.py
   apikey = "your_openai_api_key_here"
   ```

## Usage

Run the `main.py` script:

```bash
python main.py
```

Follow the on-screen instructions and speak commands to interact with HacktivAssistant. Use the keyword "HacktivAssistant" to wake up the assistant and begin giving commands.

## Features

- Voice-controlled interaction using SpeechRecognition.
- Web browsing capabilities with commands like "Open YouTube" or "Search Wikipedia."
- Music playback with the command "Open Music."
- Time-check feature with the command "What's the time?"
- AI-driven chatbot conversations using OpenAI's GPT-3.5 Turbo.

## Dependencies

- Python 3.x
- SpeechRecognition
- OpenAI GPT-3.5 Turbo
- Other dependencies specified in `requirements.txt`

## Configuration

- Ensure that you have a valid OpenAI API key and configure it in the `config.py` file.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
