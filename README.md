# -@JKU-AI-Powered-Malaria-Detection-System-Using-Deep-Learning
Malaria Detection System. README

## Project Overview

We created a system that uses intelligence to detect malaria parasites in blood cell images. Our system is quite accurate with a 93.5% success rate in telling infected blood cells apart.

## How It Works

*   Here's how it works: you upload a microscope image of a blood sample.

*   Our AI model then looks at the image. Gives a diagnosis of either HEALTHY or INFECTED along with a confidence score percentage and some clinical advice.

## Technology Stack

*   **Deep Learning Model**: We used MobileNetV2 with METHOD called Transfer Learning.

*   **Backend**: Our backend is built with Python. Uses METHOD called Flask.

*   **Frontend**: For the frontend we used HTML, CSS and JavaScript.

*   **AI Framework**: We used TensorFlow Lite for our AI framework.

*   **Deployment**: We deployed our system using Hugging Face Spaces.

## Model Performance

*   **Accuracy**: Our system is 93.5% accurate.

*   **Precision**: We got a precision of 95.3%.

*   **Recall**: Our recall rate is 91.5%.

*   **F1-Score**: We achieved an F1-Score of 93.4%.

*   **File Size**: Our system has a file size of 13.34 MB.

*   **Inference Time**: It takes 0.03 seconds to process each image.

## Dataset

*   We used a total of 2000 images. 1000 Healthy and 1000 infected.

*   **Training Set**: We used 1600 images for training which's 80% of our dataset.

*   **Testing Set**: We used 400 images for testing, which's 20% of our dataset.

*   **Source**: Our dataset comes from the NIH Malaria Dataset.

## How to Use

*   First open our web interface.

*   Then. Drag and drop a blood cell image.

*   Next click the Detect Malaria button.

*   Finally view your diagnosis results and recommendations.

## Installation, for Local Use

*   To install the required packages run: `pip install tensorflow flask pillow numpy`

*   To run the application use: `python app.py`

*   To access the system open your browser and go to `http://127.0.0.1:5000`

## GET THE SYSTEM THROUGH

*   You can try out our system online at: <https://huggingface.co/spaces/wakjira01/malaria-detection-system>

## Project Team Work

*   JINKA UNIVERSITY. Department of Computer Science

*   3rd Year G1 Students AI Academic Project 2026
