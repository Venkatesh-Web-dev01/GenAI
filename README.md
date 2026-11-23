# 💬 Generative AI Chatbot

A conversational AI web application built with **Streamlit**, **LangChain**, and **Groq**, powered by the `openai/gpt-oss-120b` model.

## Features

- **Interactive Chat UI:** Clean, centered web interface built with Streamlit (`st.chat_message` and `st.chat_input`).
- **Session-Based Memory:** Maintains conversation context across messages using `st.session_state`.
- **Fast Inference:** Uses `langchain-groq` with `openai/gpt-oss-120b` (`temperature=0.0`) for consistent, low-latency responses.
- 
