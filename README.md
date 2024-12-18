Herbal Leaf Classification using ResNet-50 and Drones

Overview

This project focuses on leveraging drones and deep learning for the automated classification of herbal leaves. It combines drone technology for image capture and the ResNet-50 model for accurate classification of leaves into predefined categories. This innovative approach facilitates real-time identification, aiding in environmental monitoring, agriculture, and herbal research.

Features

Drone-Based Image Capture: Autonomous drones capture high-quality images of herbal leaves in natural environments.

Deep Learning Model: ResNet-50 processes the captured images to classify them into predefined categories.

Real-Time Processing: Instant classification of leaves for efficient decision-making.

Application Areas: Supports research in botany, pharmaceutical sciences, and conservation efforts.

Prerequisites

Hardware:

Drone equipped with a high-resolution camera.

System with GPU support (for training and inference).

Software:

Python 3.7 or higher

TensorFlow/Keras for deep learning

OpenCV for image preprocessing

Drone SDK for navigation and image capture

Installation

Install the required dependencies:

pip install -r requirements.txt

Ensure the drone SDK is installed and configured.

Dataset Preparation

Gather or download a dataset of herbal leaf images.

Organize the dataset into training and testing sets, with separate folders for each category.

Preprocess the images (resize, normalize) before training.

Model Training

Use the ResNet-50 architecture pre-trained on ImageNet.

Fine-tune the model using the herbal leaf dataset:

python train_model.py

Deployment

Upload the trained model to the drone's onboard system or use an edge device for inference.

Run the drone navigation and image capture script:

python drone_capture.py

Real-time classification results will be displayed and stored.

Results

The system classifies herbal leaves with high accuracy, enabling efficient identification. Results can be visualized through the provided dashboard or stored in a database.

Future Work

Extend the dataset to include more herbal leaf categories.

Improve real-time processing speed for onboard deployment.

Integrate GPS for location-based tagging of identified plants.

Contact

For questions or collaboration, contact kanishkasj19@gmail.com
