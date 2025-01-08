# Text-summarization tool using NLP techinque.
This project is a Flask-based web application that provides text summarization and text-to-speech capabilities. Users can input raw text, receive a concise summary, and download the summary as an audio file.
The application uses Natural Language Processing (NLP) techniques for summarization and Google Text-to-Speech (gTTS) for generating audio.
Features
Text Summarization: Automatically generates a summary from user-provided text using NLP techniques.
Text-to-Speech: Converts the summarized text into an audio file.
User-Friendly Interface: A simple web interface built with Flask.
Word Frequency Analysis: Summarization is based on word frequency and sentence scoring.
Technologies Used
Backend: Python, Flask
NLP: SpaCy
Text-to-Speech: Google Text-to-Speech (gTTS)
Frontend: HTML (via Flask templates)
File Structure
c
text-summarizer/
├── app.py                 # Flask application
├── text_summary.py        # NLP-based summarizer function
├── templates/
│   ├── index.html         # Home page
│   ├── summary.html       # Summary page
├── static/
│   ├── summary.mp3        # Audio file (generated at runtime)
