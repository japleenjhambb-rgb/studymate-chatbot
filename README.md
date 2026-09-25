# studymate-chatbot
# 📚 StudyMate Chatbot

Intelligent study assistant 

**Description:** Develop chatbot systems with memory, tools, and guardrails.

## Features

- **Conversation Memory** – Remembers previous messages in the conversation
- **External Tool Integration** – Real-time web search for up-to-date information
- **Safety Guardrails** – Blocks harmful, illegal, and jailbreak attempts
- Clean and user-friendly Streamlit interface

## Learning Outcomes

- Design and implement intelligent chatbot solutions that incorporate conversation memory, external tool integration, and safety controls. **(CO2)**

## Tech Stack

- Python
- LangChain
- OpenAI (GPT-4o-mini)
- Streamlit
- DuckDuckGo Search

## Project Structure
studymate-chatbot/
├── app.py                  # Streamlit frontend
├── chatbot/
│   ├── agent.py            # Main chatbot agent
│   ├── memory.py           # Conversation memory
│   ├── tools.py            # External tools (Web Search)
│   └── guardrails.py       # Safety controls
├── requirements.txt
├── .env.example
└── README.md

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/japleenjhambb-rgb/studymate-chatbot.git
   cd studymate-chatbot
   python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env
streamlit run app.py
