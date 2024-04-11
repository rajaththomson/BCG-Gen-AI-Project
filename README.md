---

# NLTK and GPT Enhanced Financial Chatbot (FinBot)

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](#)
[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](#)
[![OpenAI API](https://img.shields.io/badge/OpenAI-GPT--3.5%20Turbo-red.svg)](#)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](#)

FinBot is a Flask-based chatbot enhanced with Natural Language Processing (NLP) capabilities using NLTK and powered by the advanced generative abilities of OpenAI's GPT-3.5 Turbo. Designed to make financial data accessible and actionable through natural language queries, FinBot serves as a bridge between complex financial information and users, enabling queries about financial metrics such as revenue and earnings of companies in an intuitive conversational manner.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Features
- **Natural Language Understanding**: Uses NLTK for sophisticated text processing, including tokenization and part-of-speech tagging.
- **Generative AI Integration**: Leverages OpenAI's GPT-3.5 Turbo for dynamic, contextually relevant responses to complex queries.
- **Flask Web Application**: A user-friendly web interface that facilitates easy interaction with the chatbot.
- **Financial Insights**: Provides actionable financial insights through natural language queries, making it easier to access and understand financial data.

## Prerequisites
- Python 3.x
- Flask, NLTK, pandas, OpenAI
- An OpenAI API key

## Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/rajaththomson/BCG-Gen-AI-Project.git
cd BCG-Gen-AI-Project
pip install -r requirements.txt
```

Ensure NLTK datasets are downloaded:

```python
import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('wordnet')
```

Set your OpenAI API key in your environment or directly in the application.

## Usage

Start the Flask app:

```bash
python app.py
```

Navigate to `http://127.0.0.1:5001/` in your web browser to interact with FinBot.

## Screenshots

### Chatbot Interface

<img width="518" alt="Screenshot 2024-04-11 012809" src="https://github.com/rajaththomson/BCG-Gen-AI-Project/assets/40268159/36187b5f-cf22-4303-bef3-de9ddfd4dbea">

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments

- NLTK Team for their incredible NLP library.
- OpenAI for making advanced AI accessible.
- Flask for being an excellent web framework for Python.

## Contact

Mathew Rajat Thomson

Project Link: [https://github.com/rajaththomson/BCG-Gen-AI-Project](https://github.com/rajaththomson/BCG-Gen-AI-Project)

---
