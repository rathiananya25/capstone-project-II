Self-Supervised Vision Transformer for Pneumonia Detection
Overview
Pneumonia is a serious respiratory disease that requires early diagnosis for effective treatment. This project presents an AI-powered system that detects pneumonia from chest X-ray images using a Vision Transformer (ViT) model. The model analyzes medical images and classifies them into Normal or Pneumonia categories.
The system leverages deep learning and self-supervised learning techniques to extract meaningful visual features from X-ray images, reducing dependency on large labeled datasets. This approach helps improve diagnostic accuracy and supports healthcare professionals in faster medical decision-making.
Problem Statement
Manual analysis of chest X-ray images by radiologists can be time-consuming and prone to human error. In many healthcare facilities, especially in resource-limited regions, there is a shortage of medical experts.
This project aims to develop an automated AI-based diagnostic tool that assists doctors by quickly analyzing chest X-ray images and detecting pneumonia with high accuracy.
Proposed Solution
The proposed system uses a Vision Transformer architecture that divides an input image into patches and processes them using an attention mechanism. This allows the model to capture global relationships in the image and identify infection patterns in lung regions.
The system pipeline includes:
Data collection and preprocessing
Model training using Vision Transformer
Pneumonia prediction and visualization
Key Features
AI-based pneumonia detection from chest X-ray images
Vision Transformer (ViT) architecture for improved feature learning
Self-supervised learning to reduce dependency on labeled datasets
Automated image preprocessing and classification pipeline
Explainable predictions using attention visualization
Technology Stack
Frontend
Streamlit / Simple Web Interface
Backend
Python
Tools & Frameworks
PyTorch / TensorFlow
OpenCV
NumPy
Pandas
Matplotlib
Scikit-learn
Cloud Platform
Google Colab / Kaggle Notebook
AI / ML Models
Vision Transformer (ViT)
Convolutional Neural Network (Baseline Model)
Dataset
The dataset used for this project consists of chest X-ray images categorized as Normal or Pneumonia. The images are preprocessed using resizing, normalization, and augmentation techniques to improve model performance.
Dataset Source: Kaggle Chest X-ray Dataset
Project Architecture
Input Chest X-ray Image
Image Preprocessing
Patch Embedding
Vision Transformer Encoder
Classification Layer
Output Prediction (Normal / Pneumonia)
Performance Metrics
Metric	Value
Accuracy	~95%
Precision	~95%
Recall	~94%
F1 Score	~94.5%
Inference Time	< 1 second
Project Modules
Module 1: Data Collection & Preprocessing
Collects and prepares chest X-ray images for model training.
Module 2: Model Development & Training
Implements and trains the Vision Transformer model.
Module 3: Prediction & Visualization
Generates predictions and displays classification results.
git clone https://github.com/yourusername/pneumonia-detection-vit.git
cd pneumonia-detection-vit
pip install -r requirements.txt
python main.py
The proposed Vision Transformer model achieves higher accuracy compared to traditional CNN models, demonstrating improved ability to capture global patterns in chest X-ray images.
Future Enhancements
Multi-disease detection (TB, COVID-19, lung cancer
The proposed Vision Transformer model achieves higher accuracy compared to traditional CNN models, demonstrating improved ability to capture global patterns in chest X-ray images.
Future Enhancements
Multi-disease detection (TB, COVID-19, lung cancer)
Real-time web or mobile application
Integration with hospital radiology systems
Larger medical datasets for improved generalization
Advanced explainable AI techniques
Contributors
Ananya Rathi
Capstone Project – B.Tech Information Technology
License
This project is created for academic and research purposes.
