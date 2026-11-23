# 💬 Generative AI Chatbot

A conversational AI web application built with **Streamlit**, **LangChain**, and **Groq**, powered by the `openai/gpt-oss-120b` model.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-Fast%20Inference-orange)

A conversational AI web application built with **Streamlit**, **LangChain**, and **Groq**, powered by the `openai/gpt-oss-120b` model.


## Features

- **Interactive Chat UI:** Clean, centered web interface built with Streamlit (`st.chat_message` and `st.chat_input`).
- **Session-Based Memory:** Maintains conversation context across messages using `st.session_state`.
- **Fast Inference:** Uses `langchain-groq` with `openai/gpt-oss-120b` (`temperature=0.0`) for consistent, low-latency responses.

- 
## Project Structure

- `chatbot.py` – Main Streamlit application containing UI setup, session history management, and Groq LLM integration.
- `requirements.txt` – Python dependencies required to run the application.


## Prerequisites

- Python 3.8 or higher
- A [Groq API Key](https://console.groq.com/)


## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Venkatesh-Web-dev01/GenAI.git](https://github.com/Venkatesh-Web-dev01/GenAI.git)
   cd GenAI
