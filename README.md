🌿 Leaf Disease Detector - Smart Crop Robot
This project is a smart leaf disease detection system using CNN and image processing, integrated with AI-generated remedies and text-to-speech (TTS). It supports multiple regional languages and provides a user-friendly interface via Flask.

Features
Real-time leaf disease detection

Multi-language translation of disease names and remedies

Audio output for remedies using TTS

CNN-based classification

Web-based interface with Flask and ngrok for remote access

Interactive UI with progress loader

Model & Dataset
Model: brinjal_model.h5 (~1.8 GB)

Dataset: Hosted on Google Drive
Download all necessary files from Google Drive
Place the model file in the repo root or adjust MODEL_PATH in the code.

Installation
Clone the repository:

bash
git clone https://github.com/YOUR_USERNAME/LeafDiseaseDetector.git
cd LeafDiseaseDetector
Install all required Python dependencies:

bash
pip install -r requirements.txt
Setup
Model File:
Download brinjal_model.h5 from the Google Drive link above and place it in your project folder.

API Key:
Add your Google Gemini API key at the designated place in the code (replace "YOUR_GEMINI_API_KEY").

ngrok Token:
Paste your ngrok auth token where shown in the code for remote/public access.

Dataset (Optional):
For model training or testing, download the dataset from the provided Drive link.

Running the Application
Jupyter Notebook:
Open and run the notebook:

bash
jupyter notebook Final_Website.ipynb
Python Script:
If you have a .py version:

bash
python Final_Website.py
Accessing via ngrok:
When you run the app, a public ngrok URL will appear in the terminal—open it in your browser to use the app.

Usage
Use the web interface to upload a leaf image.

Select your preferred output language.

The app predicts the disease and provides an AI-generated remedy, along with text-to-speech audio.

Notes
Ensure you download the large model file before running the application.

Set your Google Gemini API key and ngrok token before launch.

All dependencies are listed in the requirements.txt file.
