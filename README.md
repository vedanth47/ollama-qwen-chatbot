# Ollama Qwen Chatbot

A simple command-line AI chatbot built with Python and Ollama. It uses the Qwen model to generate responses to user questions locally.

## Features

- Ask questions through the terminal.
- Generate responses using a locally running Ollama model.
- Use the Qwen 0.8B model.
- Configure response generation using model options.
- Keep responses simple, clear, and informative.

## Technologies Used

- Python
- Ollama
- Qwen 3.5 (0.8B)
- Ollama Python client

## Prerequisites

- Python installed on your computer.
- Ollama installed and running.
- The `qwen3.5:0.8b` model available in Ollama.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/ollama-qwen-chatbot.git
cd ollama-qwen-chatbot
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Install the Python dependency

```bash
pip install -r requirements.txt
```

### 3. Install and start Ollama

Download Ollama from https://ollama.com/download.

Pull the model:

```bash
ollama pull qwen3.5:0.8b
```

Ensure Ollama is running locally and the model is available before starting the chatbot.

### 4. Run the chatbot

```bash
python chatbot.py
```

Enter your question when prompted. The chatbot will display the generated response in the terminal.

## Project Structure

```text
ollama-qwen-chatbot/
├── chatbot.py
├── requirements.txt
├── README.md
└── .gitignore
```

## How It Works

1. Initializes the Ollama client.
2. Accepts a question from the user.
3. Sends the question to the selected Qwen model.
4. Receives and extracts the generated response.
5. Displays the response in the terminal.

## Learning Objectives

- Learn how to connect Python applications to Ollama.
- Run local language models.
- Send chat messages through an API client.
- Configure model generation options.
- Build a basic command-line AI application.

## Limitations

- Ollama must be running locally.
- The selected model must be downloaded.
- Response quality and speed depend on the model and available system resources.
- The current program processes one question per execution.

## Author

Add your name and GitHub profile here.
