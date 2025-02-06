# Gen-AI-With-Deep-Seek-R1

DeepSeek LocalChat
🚀 DeepSeek LocalChat is a locally hosted AI-powered chat application built using Ollama, DeepSeek, and Streamlit. This project allows you to interact with a conversational AI model entirely on your local machine, ensuring privacy and offline functionality.

Features
Local AI Chat: Run a conversational AI model locally using Ollama and DeepSeek.

Streamlit Web Interface: A simple and intuitive web app for interacting with the AI.

Privacy-First: All data stays on your machine—no external servers or APIs.

Customizable: Easily swap or fine-tune models for different use cases.

Lightweight: Designed to run efficiently on local hardware.

Prerequisites
Before running the project, ensure you have the following installed:

Python 3.8 or higher

Ollama (for running the DeepSeek model locally)

Streamlit (pip install streamlit)

Other dependencies (listed in requirements.txt)

Installation
Clone the repository:

bash
Copy
git clone https://github.com/yourusername/deepseek-localchat.git
cd deepseek-localchat
Set up a virtual environment (optional but recommended):

bash
Copy
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
pip install -r requirements.txt
Download and set up Ollama:

Follow the Ollama installation guide to set up the DeepSeek model locally.

Ensure the model is running and accessible.

Usage
Run the Streamlit app:

bash
Copy
streamlit run app.py
Open your browser:

The app will open automatically in your default browser at http://localhost:8501.

Start chatting:

Type your message in the input box and press Enter to interact with the DeepSeek model.

Customization
Change the model: Modify the app.py file to point to a different Ollama model.

Add features: Extend the Streamlit app with additional functionality like chat history, model settings, or themes.