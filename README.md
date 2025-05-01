# GitHub-week-1-repo
# 🌱 Plant Disease Detection System for Sustainable Agriculture

## 1. Deep Learning (DL)
Deep Learning is a subset of machine learning that uses neural networks with many layers to learn complex patterns in large amounts of data. It is commonly used for image recognition, speech processing, and natural language tasks.

## 2. Neural Networks (NN) and its Types
A Neural Network is a computational model inspired by the human brain. It consists of interconnected nodes (neurons) organized in layers: input, hidden, and output.

### Types of Neural Networks:
- **Feedforward Neural Network (FNN):** Basic structure; data flows in one direction.
- **Convolutional Neural Network (CNN):** Best for image-related tasks like classification and detection.
- **Recurrent Neural Network (RNN):** Best for sequential data (e.g., time series, text).
- **Radial Basis Function Network (RBF):** Uses radial basis functions as activation.
- **Generative Adversarial Network (GAN):** Used to generate new data similar to training data.

## 3. Convolutional Neural Network (CNN)
CNN is a type of deep neural network that is especially effective for image processing. It includes convolution layers for feature extraction, pooling layers for downsampling, and fully connected layers for classification. CNNs are widely used in plant disease detection to recognize leaf patterns, spots, and texture changes.

## 4. Pipeline for Plant Disease Detection System

1. **Data Collection**  
   - Collect images of healthy and diseased plants using smartphones or public datasets.

2. **Data Preprocessing**  
   - Resize images, remove noise, normalize pixel values, and augment data.

3. **Model Building (Using CNN)**  
   - Train a CNN model on the preprocessed dataset using layers like Conv2D, MaxPooling, Flatten, and Dense.

4. **Model Evaluation**  
   - Use metrics such as accuracy, precision, recall, and confusion matrix.

5. **Deployment**  
   - Integrate the trained model into a mobile or web app to enable real-time leaf image diagnosis.

6. **Sustainability Features**  
   - Promote early disease detection to reduce pesticide usage, increase crop yield, and reduce economic loss.
