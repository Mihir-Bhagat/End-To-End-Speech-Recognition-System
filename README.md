# End-To-End-Speech-Recognition-System
## Overview

This project develops an end-to-end multilingual speech processing system that integrates Automatic Speech Recognition (ASR), text correction, language translation, and Text-to-Speech (TTS) synthesis. The system uses a hybrid CNN-RNN model for ASR, dictionary-based and statistical text correction, Google Translate API for translation, and gTTS for speech synthesis. It achieves a Character Error Rate (CER) of 15.12% with the custom model and 0.87% with a pre-trained Wav2Vec 2.0 model on the LibriSpeech test-clean dataset.

Features

Speech Recognition: Custom CNN-RNN model and pre-trained Wav2Vec 2.0 for transcribing English speech.

Text Correction: Combines dictionary-based and pyspellchecker methods to improve transcription accuracy.

Translation: Supports translation into multiple languages using the Google Translate API.

Speech Synthesis: Generates natural-sounding speech in various languages using gTTS.

Modular Pipeline: Scalable architecture allows independent improvement of components.
