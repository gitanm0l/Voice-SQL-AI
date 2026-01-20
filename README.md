# VoiceSQL AI

VoiceSQL AI is a voice-enabled AI system that allows users to interact with
databases using natural spoken language. The application converts speech to text,
interprets user intent using NLP techniques, generates SQL queries, and executes
them on a database.

## Features
- Voice-based query input
- Natural language to SQL conversion
- SQLite database integration
- Streamlit user interface
- Query execution with result display

## Tech Stack
- Python
- Streamlit
- SQLite
- SpeechRecognition
- NLP

## Project Structure
- app.py – Application UI and flow
- speech_to_text.py – Voice to text conversion
- query_parser.py – NLP-based query interpretation
- sql_generator.py – SQL query generation
- database.db – Sample database

## How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
Credits

This project is inspired by open-source implementations and has been
customized, extended, and structured independently by Anmol.

