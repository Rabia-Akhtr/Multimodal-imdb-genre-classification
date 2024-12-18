# 🎬 **Multimodal IMDB Genre Classification with Keras**  

## Overview
Welcome to the **Multimodal IMDB Genre Classification** project! This repository demonstrates how to use **Keras** for genre classification of movies using two distinct data modalities:
- **Image data** (from movie posters) using **Convolutional Neural Networks (CNNs)**
- **Text data** (from movie overviews) using **Long Short-Term Memory (LSTM)** networks.

By combining these two powerful models, we aim to achieve accurate genre classification from both visual and textual data. 🎥📖

## Features 🌟

### **Two-Model Approach**:
- **CNN**: Convolutional Neural Network to classify movie genres from **posters** (JPEG images).
- **LSTM**: Long Short-Term Memory model to classify movie genres from **overviews** (text data).

### **Data Preprocessing** 🔄:
- **Image Processing**:
  - Resizing and normalization of movie posters for CNN input.
- **Text Processing**:
  - Tokenization, padding, and vocabulary building to prepare overviews for LSTM input.

### **Model Training** 💻:
- **CNN**: 
  - Built using Keras' functional API, incorporating layers such as convolution, dropout, and max-pooling.
- **LSTM**: 
  - Built using Keras' sequential API, including bidirectional LSTM layers, dense layers, and dropout layers for regularization.

### **Evaluation** 📊:
- Model performance is assessed through **loss**, **accuracy**, **precision**, and **recall** metrics.
- Visualizations (graphs) include:
  - **Loss plots** 
  - **Precision**
  - **Recall** for both models

## Files Included 📁

| File Type                      | Description                                  |
| ------------------------------ | -------------------------------------------- |
| **Main Model Code**            | `Keras_Assignment_Dec2024.ipynb`             |
| **Project Report**             | `23031641 ADS Keras.pdf`                    |
| **Model Weights**              | Saved CNN and LSTM model weights             |

## Installation and Usage 🛠️

### Step 1: Clone the Repository 📥
Clone this repository to your local machine using Git:
```bash
git clone https://github.com/your-username/multimodal-imdb-genre-classification.git
cd multimodal-imdb-genre-classification
