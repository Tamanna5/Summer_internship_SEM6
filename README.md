# AI/ML Projects Portfolio

Welcome to my collection of AI and Machine Learning projects! This repository contains various implementations ranging from speech recognition to legal document analysis, personality prediction, and facial emotion detection.

## 🚀 Projects Overview

### 1. [Legal Document Analysis & Summarization](https://github.com/Tamanna5/legal_document.git)
**AI-driven system for analyzing and summarizing legal documents using advanced NLP techniques.**

**Features:**
- Web interface for document upload and analysis
- Supports PDF, DOCX, and TXT formats
- Smart summarization generating concise 1-2 page summaries
- Key information extraction (legal entities, clauses, obligations)
- Multiple output formats (PDF and JSON)
- Professional document formatting

**Tech Stack:** Flask, spaCy, NLTK, transformers, PDF processing

### 2. [Speech Recognition System](https://github.com/Tamanna5/speech_recognition.git)
**Comprehensive speech recognition project with multiple implementations.**

**Features:**
- **Basic Implementation:** Audio recording, processing, and visualization
- **Simple Speech Recognition:** Speech-to-text using AssemblyAI API with multiple language support
- **Sentiment Analysis:** YouTube video audio analysis with transcription and sentiment analysis
- **Virtual Assistant:** Advanced speech processing capabilities

**Tech Stack:** Python, PyAudio, AssemblyAI API, FFmpeg, yt-dlp

### 3. [Personality Prediction System - CV Analysis](https://github.com/Tamanna5/Personality_Prediction_System_CV_Analysis.git)
**Modern web application that predicts personality traits from CV/resume documents using NLP and machine learning.**

**Features:**
- Modern, unique UI with gradient design and responsive layout
- File upload and retention (PDF, DOCX, TXT formats)
- AI-powered personality prediction with confidence scores
- Live results display without page reload
- Model training endpoint for custom data

**Tech Stack:** Flask, HTML/CSS, Python, Machine Learning, NLP

### 4. [Facial Emotions Detection](https://github.com/Tamanna5/Facial-Emotions-Detection.git)
**Real-time facial emotion recognition system using deep learning.**

**Features:**
- Real-time emotion detection from webcam feed
- Pre-trained deep learning model for accurate emotion classification
- Support for multiple emotion categories
- Easy-to-use interface for emotion analysis

**Tech Stack:** Python, OpenCV, TensorFlow/Keras, Deep Learning

## 📁 Project Structure

```
summer_internship_sem6/
├── legal_document/                    # Legal document analysis system
│   ├── main.py                       # Application entry point
│   ├── web_app.py                    # Flask web application
│   ├── document_processor.py         # Document processing
│   ├── entity_extractor.py           # Entity recognition
│   ├── summarizer.py                 # Document summarization
│   └── templates/                    # Web interface templates
│
├── speech_recognition/               # Speech recognition implementations
│   ├── basic/                       # Basic audio processing
│   ├── simple_speech_recognition/   # Speech-to-text conversion
│   ├── sentiment_analysis/          # YouTube sentiment analysis
│   └── virtual_assistant/           # Virtual assistant features
│
├── Personality_Prediction_System_CV_Analysis/  # CV personality prediction
│   ├── main_app.py                  # Main application
│   ├── synthetic_cv_data.csv        # Training data
│   ├── templates/                   # UI templates
│   └── uploads/                     # Uploaded files
│
├── Facial-Emotions-Detection/       # Facial emotion recognition
│   ├── facial_emotion_recognition.py # Main emotion detection script
│   ├── model_weights.h5            # Pre-trained model
│   ├── requirements.txt             # Dependencies
│   └── dataset/                    # Training dataset
│
└── README.md                       # This file
```

## 🛠️ Common Prerequisites

- **Python 3.8+**
- **FFmpeg** (for audio processing projects)
- **Internet connection** (for API-based implementations)
- **Webcam** (for facial emotion detection)
- **AssemblyAI API key** (for speech recognition)

## 🚀 Quick Start

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Tamanna5/summer_internship_sem6.git
   cd summer_internship_sem6
   ```

2. **Install common dependencies:**
   ```bash
   pip install numpy matplotlib PyAudio wave requests yt-dlp flask spacy nltk transformers torch pdfplumber python-docx reportlab werkzeug opencv-python tensorflow
   ```

3. **Install FFmpeg:**
   - **macOS:** `brew install ffmpeg`
   - **Ubuntu/Debian:** `sudo apt-get install ffmpeg`
   - **Windows:** Download from [FFmpeg website](https://ffmpeg.org/download.html)

4. **Download required models:**
   ```bash
   python -m spacy download en_core_web_lg
   python -c "import nltk; nltk.download('punkt'); nltk.download('stopwords')"
   ```

## 🎯 Learning Path

1. **Start with Basic Projects:** Begin with the basic speech recognition implementation to understand audio processing fundamentals
2. **Explore Web Applications:** Move to the legal document analysis and personality prediction systems to learn web development with AI
3. **Advanced AI:** Explore the facial emotion detection for computer vision applications
4. **API Integration:** Learn about external API usage with the speech recognition project

## 🔗 Individual Project Links

- **[Legal Document Analysis](https://github.com/Tamanna5/legal_document.git)** - AI-powered legal document summarization
- **[Speech Recognition](https://github.com/Tamanna5/speech_recognition.git)** - Comprehensive speech processing system
- **[Personality Prediction System](https://github.com/Tamanna5/Personality_Prediction_System_CV_Analysis.git)** - CV-based personality analysis
- **[Facial Emotions Detection](https://github.com/Tamanna5/Facial-Emotions-Detection.git)** - Real-time emotion recognition

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest improvements
- Add new features
- Improve documentation
- Submit pull requests

## 📝 License

This project is licensed under the MIT License - see the individual project repositories for details.

## 👨‍💻 Author

**Tamanna Kalariya**

- GitHub: [@Tamanna5](https://github.com/Tamanna5)
- Portfolio showcasing AI/ML projects with focus on:
  - Natural Language Processing
  - Computer Vision
  - Speech Recognition
  - Web Development with AI integration