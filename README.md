# AI-GYM-TRAINER

AI Gym Trainer is an innovative project designed to bring artificial intelligence into fitness training. It helps users monitor, analyze, and improve their workout routines using AI-based techniques, computer vision, and real-time feedback.

# Features
Real-time exercise tracking and feedback.
Body posture analysis using computer vision.
Integration of audio cues for guidance.
Interactive and easy-to-use interface powered by Streamlit.

# Requirements
The following Python libraries are required to run the project:

aiortc (v1.3.0): For WebRTC connections.
av (v8.1.0): A binding for FFmpeg to work with multimedia.
matplotlib (v3.5.1): For generating visualizations and graphs.
numpy (v1.21.4): For numerical computations.
opencv-python-headless (v4.5.5.62): For image processing and computer vision tasks.
pydub (v0.25.1): For audio manipulation and playback.
streamlit (v1.5.1): For creating the interactive user interface.
streamlit-webrtc (v0.35.2): For adding real-time video/audio streaming features.
typing_extensions (v4.1.1): For supporting type hints in Python.

# Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Sahil-Gupta628/AI-GYM-TRAINER.git
cd AI-GYM-TRAINER
Set up a virtual environment:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate    # For Linux/MacOS
venv\Scripts\activate       # For Windows
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
How to Run
Start the application using Streamlit:

bash
Copy
Edit
streamlit run app.py
Open the link provided in your terminal (usually http://localhost:8501/) to access the AI Gym Trainer interface.

Follow the instructions in the app to start your workout session.
