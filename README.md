# AI Security Challenge

A Streamlit-based AI security challenge application that uses Ollama for local AI model inference.

## Prerequisites

- Python 3.8 or higher
- [Ollama](https://ollama.ai/) installed locally
- Mistral model pulled in Ollama

## Setup

1. Install Python dependencies:
```bash
pip install -r requirements.txt
```

2. Make sure Ollama is running with Mistral model:
```bash
ollama run mistral
```

## Running the Application

1. Start the Streamlit app:
```bash
streamlit run app.py
```

2. Open your browser and navigate to the URL shown in the terminal (usually http://localhost:8501)

## Notes

- The application requires Ollama to be running locally on port 11434
- Make sure you have the Mistral model pulled in Ollama before starting the application
- The application uses session-based chat history, so each browser session will maintain its own conversation 