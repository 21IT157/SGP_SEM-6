# Leaf Diseases Detection using Deep Learning
This repository contains code for detecting diseases in Cassava leaves using Deep Learning techniques, particularly focusing on Vision Transformer Model.



## Overview
Cassava is one of the most important food crops in the world, providing a significant source of calories for millions of people. However, it is susceptible to various diseases that can significantly reduce crop yields. Early detection of these diseases is crucial for effective management and prevention of yield losses.
This project aims to develop a deep learning-based system for automated detection of diseases in Cassava leaves. We utilize the state-of-the-art Vision Transformer Model, which has shown remarkable performance on various computer vision tasks.



## Dataset
The dataset used in this project consists of high-resolution images of Cassava leaves affected by different diseases, along with healthy leaves for comparison. The dataset is obtained from Kaggle : Link for the Dataset  https://www.kaggle.com/competitions/cassava-leaf-disease-classification/data.



## Model Architecture

The theory behind the Transformer Vision Model (TVM) stems from the original Transformer architecture proposed by Vaswani et al. for natural language processing (NLP) tasks. The Transformer architecture revolutionized NLP by introducing self-attention mechanisms, enabling the model to capture long-range dependencies within sequences efficiently. Building upon this success, researchers extended the Transformer architecture to the domain of computer vision, giving rise to the Transformer Vision Model.

**Self-Attention Mechanism**:
At the heart of the Transformer architecture lies the self-attention mechanism. In the context of vision, the self-attention mechanism allows the model to capture relationships between different regions (or patches) within an image. This is achieved by computing attention scores that indicate the importance of each patch with respect to every other patch in the image. By attending to relevant regions, the model can extract meaningful spatial information from the input image.

**Patch Embeddings**:
Unlike traditional convolutional neural networks (CNNs), which operate directly on pixel values, Transformer Vision Models treat images as sequences of non-overlapping patches. Each patch is embedded into a high-dimensional vector space, allowing the model to process spatial information in a structured manner. This patch-based approach enables Transformer Vision Models to handle images of arbitrary size without the need for resizing or cropping.

**Multi-Head Attention**:
Transformer Vision Models typically employ multi-head attention mechanisms, where the self-attention operation is performed multiple times in parallel with different sets of learnable parameters. This enables the model to attend to different aspects of the input image simultaneously, facilitating richer representations and enhanced generalization capabilities.

**Positional Encoding**:
Incorporating positional information is crucial for preserving spatial relationships between patches in the absence of explicit positional encodings as in CNNs. Transformer Vision Models utilize positional encodings to inject spatial information into the input embeddings, allowing the model to differentiate between patches based on their positions within the image.

**Feed-Forward Networks**:
Following the self-attention layers, Transformer Vision Models typically include feed-forward neural networks (FFNNs) to process the attended features and generate context-aware representations. These FFNNs consist of multiple layers of fully connected neural networks, enabling the model to capture complex spatial patterns and interactions within the image.

**Training and Optimization**:
Transformer Vision Models are trained using standard backpropagation algorithms with optimization techniques such as stochastic gradient descent (SGD) or its variants. Pretraining on large-scale datasets followed by fine-tuning on task-specific data has been shown to be effective in achieving state-of-the-art performance across various computer vision tasks.

## Requirements
All the dependencies required to build this project has been mentioned in the requirement.txt file. Make sure berofre you execute this codes. You have installed the prerequisite in you local computer

--
