# Telugu Handwriting Recognition using CNN and RNN

This project focuses on recognizing handwritten Telugu characters and words
using deep learning techniques. Convolutional Neural Networks (CNN) are used
to extract visual features from handwritten images, while Recurrent Neural
Networks (RNN) are used to model the sequential nature of Telugu handwriting.

The project explores different model variations, ranging from basic to
advanced architectures, to study their performance in handwritten text
recognition.

---

## Project Objectives

- To recognize handwritten Telugu characters and words
- To study the role of CNN in image feature extraction
- To understand how RNN helps in sequence learning
- To compare basic and advanced CNN–RNN architectures
- To analyze accuracy and performance of different models

---

## 🧠 Model Approaches Used

### 1️⃣ CNN Only Model
- Uses Convolutional Neural Networks
- Extracts spatial features from handwritten character images
- Suitable for single character recognition

### 2️⃣ RNN Only Model
- Uses Recurrent Neural Networks
- Focuses on sequential dependencies in handwriting
- Useful for understanding character sequences

### 3️⃣ Basic CNN + RNN Model
- CNN for feature extraction
- RNN for sequence modeling
- Simple architecture for understanding core concepts

### 4️⃣ Advanced CNN + RNN Model
- Deeper CNN layers for better feature learning
- Advanced RNN (LSTM/GRU) for improved sequence prediction
- Higher accuracy and better generalization

---
Dataset Used

For training and testing the handwriting recognition models in this project, we used the Telugu handwritten word dataset released by the Centre for Visual Information Technology (CVIT), IIIT Hyderabad.

This dataset is part of the Indic Handwritten Word Dataset which contains word-level images written by multiple writers. Specifically:

IIIT-HW-Telugu: Contains over 120,000 Telugu handwritten word images for offline handwriting recognition. 
cvit.iiit.ac.in

The dataset includes a README file and labels to facilitate training deep learning models. 
cvit.iiit.ac.in

📥 Download link:
https://cvit.iiit.ac.in/research/projects/cvit-projects/indic-hw-data


## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- OpenCV (for image preprocessing)

---

## How to Run the Project

1. Install required libraries:
pip install tensorflow numpy opencv-python

2. Run individual models:
python cnn_only.py
python rnn_only.py
python basic_cnn_rnn.py
python advanced_cnn_rnn.py


---

## Results & Observations

- CNN models perform well for isolated character recognition
- RNN improves recognition of sequential handwritten patterns
- Combined CNN + RNN models achieve better accuracy
- Advanced models outperform basic models in complex handwriting cases

---

## Learning Outcomes

- Understanding of CNN for image feature extraction
- Practical knowledge of RNN for sequence modeling
- Experience with deep learning model design
- Hands-on exposure to handwriting recognition systems
- Comparative analysis of basic and advanced architectures

---

## Future Enhancements

- Use larger and more diverse datasets
- Apply data augmentation techniques
- Integrate Attention mechanisms
- Extend the model for real-time handwriting recognition

---

## Author

Anamala Muni Cherisma  
