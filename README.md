# 🌿 Leaf Disease Detector - Smart Crop Robot

This project is a **smart leaf disease detection system** using **CNN and image processing**, integrated with **AI-generated remedies** and **text-to-speech (TTS)**. It supports multiple regional languages and provides a user-friendly interface via Flask.

## Features
- Real-time leaf disease detection
- Multi-language translation of disease and remedies
- Audio output for remedies using TTS
- CNN-based classification
- Web-based interface with Flask + ngrok
- Interactive UI with progress loader

## Model & Dataset
- **Model:** `brinjal_model.h5` (~1.8 GB)
- **Dataset:** Hosted on Google Drive  
Download all necessary files from [Google Drive](https://drive.google.com/drive/folders/1QxLu-xneHZdck71vjZm3jtUIcbs98R5l)  
Place the model file in the repo root or adjust `MODEL_PATH` in the code.

## Setup Instructions (Colab / Local)
1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/LeafDiseaseDetector.git
cd LeafDiseaseDetector
