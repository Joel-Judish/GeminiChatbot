# AI Chatbot using Google GeminiAPI

## Gemini-Pro Chatbot

This repository contains a simple chatbot application built using Google Gemini-Pro and Streamlit. The chatbot interacts with users in a conversational manner, leveraging Google Gemini's advanced generative AI capabilities.

## Features
- Integrates with Google Gemini-Pro API for conversational AI.
- Streamlit-based user interface for interactive chat.
- Maintains chat history during a session for better context.
- Simple and intuitive design to accept user prompts and display AI-generated responses.

## Requirements
- Python 3.x
- A valid Google Gemini-Pro API key.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/gemini-pro-chatbot.git
   cd gemini-pro-chatbot
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the project root and add your Google Gemini-Pro API key:
   ```env
   GOOGLE_GEMINI_KEY=your_api_key_here
   ```

## Usage
1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```
2. Open the URL displayed in your terminal (usually `http://localhost:8501`).
3. Enter your queries in the input box, and the chatbot will respond with AI-generated replies.

## File Structure
- `app.py`: Main application script for Streamlit.
- `requirements.txt`: List of dependencies required to run the application.
- `.env`: Environment file to store sensitive API keys (not included in the repository).
- `.gitignore`: Ensures sensitive files like `.env` are not pushed to version control.

## Environment Variables
- `GOOGLE_GEMINI_KEY`: API key for authenticating with the Google Gemini-Pro API.

## Example Output
```text
Gemini-Pro Chatbot
------------------
Ask me something...! [User Input]
User: "What is the capital of France?"
Assistant: "The capital of France is Paris."
```

## References
- [Streamlit Documentation](https://docs.streamlit.io/)
- [Google Generative AI API](https://developers.generativeai.google/)
- [dotenv Python Package](https://pypi.org/project/python-dotenv/)

## License
This project is licensed under the MIT License. See the LICENSE file for details.


