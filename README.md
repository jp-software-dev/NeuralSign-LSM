# NeuralSign-LSM

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)

An advanced Computer Vision and Deep Learning engine developed in Python. It maps 21 articular nodes of the hand in real-time to translate Mexican Sign Language (LSM) into text and voice, featuring a gamified learning module for interactive practice.

## Features

* **Real-time Translation:** Highly accurate hand mapping utilizing neural networks to classify the A-Z alphabet and formal phrases.
* **Voice Assistant Integration:** An offline Text-to-Speech (TTS) bot that vocalizes detected signs instantly without latency.
* **Gamified Learning Mode:** An interactive hangman-style game where users spell random words using physical sign language to progress.
* **Fail-safe Architecture:** Automated internal logging system and a modular structure separating the AI engine from the UI.

## Technologies Used

* **Core Language:** Python 3.x
* **Computer Vision:** OpenCV, MediaPipe
* **Machine Learning:** TensorFlow / Keras, NumPy, Pandas
* **Accessibility:** pyttsx3 (Text-to-Speech)

## Installation & Setup

Follow these steps to deploy the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/jp-software-dev/NeuralSign-LSM.git
