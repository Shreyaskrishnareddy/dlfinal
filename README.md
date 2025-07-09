# dlfinal

![Python](https://img.shields.io/badge/python-3.8+-blue.svg) ![License](https://img.shields.io/badge/license-MIT-blue.svg) ![FastAPI](https://img.shields.io/badge/FastAPI-3.0.0-blue.svg) ![LangChain](https://img.shields.io/badge/LangChain-0.1.0-blue.svg) ![OpenCV](https://img.shields.io/badge/OpenCV-4.5.3-blue.svg)

## 🚀 Overview

The `dlfinal` project is a Python application that utilizes FastAPI, LangChain, and OpenCV to create a conversational AI system. This system allows users to interact with a chat model using a graphical user interface (GUI) built with Gradio. The chat model is powered by Google GenAI's Chat API and OpenAI's Chat API, enabling users to engage in natural language conversations.

## ✨ Key Features

* Conversational AI system with a GUI interface built using Gradio
* Integration with Google GenAI's Chat API and OpenAI's Chat API for chat model capabilities
* Support for loading environment variables from a .env file
* Video capture and image encoding using OpenCV
* Image processing using PIL
* Support for displaying HTML widgets in Jupyter notebooks using IPython

## 🛠️ Technology Stack

### Core Technologies

* FastAPI: A modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints.
* LangChain: A Python library for building conversational AI systems using a modular architecture.
* OpenCV: A computer vision library for image and video processing.

### Dependencies

* IPython: A command-line tool that allows you to run Python code in the browser.
* PIL: A Python Imaging Library for image processing.
* asyncio: A library for writing single-threaded concurrent code using coroutines, multiplexing I/O access over sockets and other resources, and implementing network clients and servers.
* base64: A module for encoding and decoding binary data using Base64.
* cv2: A library for image and video processing using OpenCV.
* dotenv: A library for loading environment variables from a .env file.
* fastapi: A modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints.
* gradio: A Python library for building GUI interfaces for machine learning models.
* gtts: A library for text-to-speech conversion using Google Text-to-Speech.
* io: A module for input/output operations.
* ipywidgets: A library for building interactive widgets in Jupyter notebooks.
* json: A module for working with JSON data.
* langchain: A Python library for building conversational AI systems using a modular architecture.
* langchain_community: A community-driven library for building conversational AI systems using LangChain.
* langchain_core: A library for building conversational AI systems using a modular architecture.
* langchain_google_genai: A library for integrating Google GenAI's Chat API with LangChain.
* langchain_openai: A library for integrating OpenAI's Chat API with LangChain.
* livekit: A library for building real-time communication applications.

## 🚀 Quick Start

### Prerequisites

* Python 3.8+
* Node.js (for Gradio)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/username/dlfinal.git
   cd dlfinal
   ```

2. **Set up environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configuration**
   Load environment variables from a .env file using the `dotenv` library:
   ```python
   from dotenv import load_dotenv
   load_dotenv()
   ```

### Usage

1. **Run the application**
   ```bash
   uvicorn main:app --reload
   ```

2. **Open the GUI interface**
   Open a web browser and navigate to `http://localhost:8000`

## 📊 Project Structure

The project structure is as follows:
```markdown
dlfinal/
main.py
requirements.txt
.env
gui/
app.py
templates/
index.html
static/
css/
style.css
js/
script.js
models/
chat_model.py
data/
data.json
```

## 🔧 Development

### Running Tests

There are no tests in this project.

### Code Quality

There are no linting or formatting tools used in this project.

## 🚀 Deployment

There is no deployment configuration in this project.

## 📖 API Documentation

There is no API documentation in this project.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

This project uses the following libraries and frameworks:

* FastAPI: A modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints.
* LangChain: A Python library for building conversational AI systems using a modular architecture.
* OpenCV: A computer vision library for image and video processing.