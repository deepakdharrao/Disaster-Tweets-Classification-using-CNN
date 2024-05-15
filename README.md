# Overview
This repository contains the implementation of a disaster tweet classification system using Convolutional Neural Networks (CNNs). The system is capable of distinguishing between real and fake disaster-related tweets with high accuracy.

# Motivation
In the age of social media, the spread of information during disasters can be chaotic and misleading. Distinguishing between real and fake information is crucial for effective disaster response and management. This project aims to leverage deep learning techniques to automatically classify disaster-related tweets, aiding in the dissemination of accurate information during critical times.

# Benefits
* Accurate Information Dissemination: By automatically classifying tweets, this system helps in ensuring that only verified information is spread during disasters, reducing panic and misinformation.
* Timely Response: Rapid identification of fake news allows authorities and organizations to focus resources on addressing real emergencies promptly.
* Industry Relevance: The technology developed in this project has significant relevance across various industries, including emergency management, news media, and social media platforms.
* Future Goals: Continuous refinement of the classification model, integration with real-time data streams, and collaboration with relevant stakeholders are among the future goals of this project.

# How to Use
Install the following dependencies for model training:
* pip install tensorflow-text
* pip install transformers -U
* pip install accelerate -U
* pip install transformers[torch]
* pip install keras-tuner

Install the following dependencies for GUI:
* pip install transformers -U
* pip install tensorflow-text
* pip install accelerate -U
* pip install transformers[torch]
* pip install -q gradio

# Dataset details
"Disaster Tweets", Kaggle. Accessed on: Apr. 24, 2024. [Online]. Available: https://www.kaggle.com/datasets/vstepanenko/disaster-tweets
