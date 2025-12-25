🎶 Whispers of the Wires

A Generative AI Music Creation Platform

📌 Overview

Whispers of the Wires is a full-stack generative AI web application that creates music based on user prompts or moods. The system combines state-of-the-art music generation models with audio classification techniques to deliver mood-aware, genre-informed musical compositions through an interactive web interface.

This project was developed during the AI Intern role at Infosys Springboard (Jul 2025 – Nov 2025).

🚀 Features

🎼 AI Music Generation using text prompts or moods

🎧 Genre Classification using pretrained audio models

😊 Mood-aware prediction with ~85% accuracy

📂 Music Library & Playlists for generated tracks

🌐 Full-stack web application with seamless frontend–backend integration

🧠 Tech Stack
Backend

FastAPI – API development

Flask / HTTP Server – Local model serving

PyTorch – Model inference

MusicGen (Meta) – Music generation

YAMNet & GTZAN – Genre classification

Librosa, SciPy – Audio processing

Frontend

HTML5

CSS3

JavaScript

🏗️ System Architecture

User provides a prompt or mood via frontend

Request is sent to FastAPI backend

MusicGen generates music audio

YAMNet + GTZAN classify genre and mood

Audio is processed using Librosa & SciPy

Generated music is returned and stored in the Library / Playlist

📄 Pages Implemented

Home – Introduction and navigation

Composition – Music generation interface

Library – Saved generated tracks

Playlist – User-curated playlists

Predict – Mood & genre prediction

⚙️ Installation & Setup
Prerequisites

Python 3.9+

PyTorch

FastAPI

Flask

Librosa

SciPy

Clone the Repository
git clone https://github.com/your-username/whispers-of-the-wires.git
cd whispers-of-the-wires

Install Dependencies
pip install -r requirements.txt

Run Backend
uvicorn main:app --reload

Run Model Server
python model_server.py

Open Frontend

Open index.html in your browser or serve it via a local server.

📊 Model Performance

Mood-aware classification accuracy: ~85%

Supports multiple genres and emotional contexts

📚 Learning Outcomes

Full-stack AI application development

Asynchronous API handling

Audio signal processing

Model deployment and integration

End-to-end coordination between frontend and backend

🔮 Future Enhancements

Cloud deployment (AWS/GCP/Azure)

User authentication

Real-time audio streaming

Improved multi-label emotion detection
