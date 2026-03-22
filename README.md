# ChatBot with Python
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/downloads/)

An educational open-source project demonstrating the fundamentals of **Natural Language Processing (NLP)** and conversational AI logic using Python.

## Overview
This project is designed to help developers understand how a chatbot can recognize user intents and generate appropriate responses using a local dataset, without relying on expensive external APIs.

## Project Goals
* **NLP Fundamentals:** Introduce core concepts of text vectorization and similarity.
* **Intent Recognition:** Show how to map user patterns to specific response categories.
* **Lightweight Architecture:** Provide a fully functional, local AI chatbot that runs offline.

## Technologies Used
* **Python 3.x**: Core logic and development.
* **scikit-learn**: For **TF-IDF Vectorization** and **Cosine Similarity**.
* **NumPy**: Efficient numerical operations.
* **JSON**: Structured dataset for intents and responses.

## Project Structure
```text
ChatBot-with-Python/
├── chatbot.py           # Core NLP & Chatbot logic
├── intents.json         # Dataset (Patterns & Responses)
├── requirements.txt     # Python dependencies
├── README.md            # Documentation
└── LICENSE              # MIT License file
