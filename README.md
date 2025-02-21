🌿 Rice Plant Disease Detection using Deep Learning

📌 Project Overview
This project focuses on detecting rice plant diseases using Convolutional Neural Networks (CNNs) and Transfer Learning (VGG16). The goal is to classify 6 different leaf disease categories based on image data.

🛠️ Methodology
Data Augmentation: Used ImageDataGenerator to apply transformations like rotation, zoom, and flipping.
Model Architecture: Leveraged the VGG16 pre-trained model with custom Dense & Dropout layers.
Training: Applied Categorical Crossentropy Loss and Adam Optimizer for multi-class classification.
Evaluation: Measured model accuracy & loss using validation data.
Prediction: Built a function to predict leaf disease based on input images.

📊 Model Performance
Training Accuracy: Achieved through fine-tuning CNN layers.
Validation Accuracy: Evaluated using unseen test data.
Graphical Analysis: Plotted accuracy vs. loss curves to analyze performance.

📂 Dataset Details
Source: Rice leaf diseases dataset
Classes: 6 categories of rice plant diseases
Image Format: .jpg, resized to 224x224 pixels for VGG16 compatibility.

📌 Key Libraries Used
Keras
Matplotlib
NumPy
🔥 Results
The model successfully classifies rice leaf diseases with high accuracy and can be used for agricultural disease detection.
