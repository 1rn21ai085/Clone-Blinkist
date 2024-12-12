Blinkist Clone
A real-time text summarization tool inspired by Blinkist, built using Flask, Socket.IO, and the Facebook BART-large-CNN model. This project allows users to upload PDF files, generate concise summaries, and even create audio versions of the summaries.

Features

Real-Time Summarization: Summarize large texts in real-time using the Facebook BART-large-CNN model.
PDF Upload: Upload PDF files for summarization.
Text Preprocessing: Automatically cleans and preprocesses text by removing unnecessary sections (e.g., table of contents, prefaces).
Chunking: Splits large texts into smaller chunks for efficient summarization.
Audio Generation: Converts summaries into audio files using text-to-speech (TTS).
Readability Metrics: Calculates readability scores (Flesch-Kincaid Grade, Gunning Fog Index, Coleman-Liau Index) for the generated summaries.
User-Friendly Interface: A clean and intuitive web interface for uploading files, viewing summaries, and downloading results.

Technologies Used

Backend: Flask (Python web framework)
Real-Time Communication: Socket.IO
Summarization Model: Facebook BART-large-CNN (via Hugging Face Transformers)
Text Preprocessing: PyPDF2, re, textstat
Audio Generation: pyttsx3
Frontend: HTML, CSS, JavaScript

Installation Prerequisites

Before running the project, ensure you have the following installed:

Python 3.7 or higher
pip (Python package manager)
Git
