✈️ Aircraft Damage Detection Using VGG16 & Vision Transformers

An automated system for detecting and describing aircraft surface damage.

📌 Overview

Aircraft damage detection is essential for ensuring flight safety, reducing maintenance time, and preventing costly failures. Traditional manual inspection methods are often slow, labor-intensive, and prone to human error.

This project automates aircraft damage analysis by combining deep learning–based image classification with AI-powered caption generation.

🔍 What This Project Does
✅ 1. Damage Classification (Dent vs. Crack)

Uses a pre-trained VGG16 model for feature extraction.

Custom classifier on top of VGG16 distinguishes between two types of damage:

Dent

Crack

Achieves fast and accurate predictions on aircraft surface images.

🧠 2. Image Captioning & Summaries (Transformer Model)

A pre-trained Transformer model is used to:

Generate descriptive captions for the image

Produce summaries that explain the detected damage

Helps maintenance teams understand results quickly and clearly.

🎯 Project Goals

Automate aircraft damage inspection

Improve accuracy and consistency of damage detection

Reduce the time needed for visual inspection

Provide descriptive text outputs using AI

🛠️ Technologies Used

TensorFlow / Keras

VGG16 (pre-trained) for image feature extraction

Transformer-based models for captioning

Matplotlib for visualization

NumPy & Pandas for preprocessing

📁 Dataset

Images of aircraft surfaces labeled as dent or crack

Preprocessed and fed into both CNN and Transformer pipelines

📊 Results

Accurate classification between dent and crack

Automatic generation of captions describing the damage

Combined visual + textual outputs for enhanced interpretability
