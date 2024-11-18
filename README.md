# Interactive Image Classifier

An interactive web application built with Streamlit and TensorFlow's MobileNetV2 model to classify images uploaded by the user. The app provides real-time predictions and displays the top 3 labels from the ImageNet dataset.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The **Interactive Image Classifier** project allows users to upload an image and receive classification predictions using a pre-trained MobileNetV2 model. This tool is designed for ease of use and showcases the power of deep learning in image recognition.

## Features
- **Upload Images**: Supports `.jpg`, `.jpeg`, and `.png` image formats.
- **Image Display**: Shows the uploaded image in the browser.
- **Real-time Predictions**: Displays the top 3 classification predictions with labels and confidence scores.
- **Responsive Design**: Adaptable to various screen sizes.

## Installation
Follow these steps to set up the project locally:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/Interactive_Image_Classifier.git
    cd Interactive_Image_Classifier
    ```

2. **Install the required packages**:
    Ensure you have Python installed. Install dependencies using pip:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Streamlit app**:
    ```bash
    streamlit run Interactive_Image_Classifier.py
    ```

## Usage
- Open your web browser and navigate to `http://localhost:8501/` (or the URL provided by Streamlit).
- Click on the **Upload** button and select an image file.
- View the uploaded image and wait for the classification results.

## Project Structure
