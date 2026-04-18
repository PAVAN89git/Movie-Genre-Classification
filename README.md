# Movie Genre Classification using Deep Learning

# Project Overview
This project predicts movie genres from poster images using deep learning techniques.

# Models Used
- CNN (Convolutional Neural Network) - Baseline model
- MobileNetV2 (Transfer Learning) - Improved model

# Preprocessing
- Image resizing to 224x224
- Normalization (0–1 scaling)
- Train-validation split (80-20)

# Results
- CNN: Overfitting (~45% validation accuracy)
- MobileNetV2: Improved (~62% validation accuracy)

# Key Learnings
- CNN may overfit on small datasets
- Transfer learning improves performance
- Visual similarity can cause misclassification

# Sample Prediction
The model can take a movie poster and predict its genre.

# Technologies Used
- Python
- TensorFlow / Keras
- Google Colab

# How to Run
1. Upload dataset
2. Run the notebook (`genre.ipynb`)
3. Test with new images

# Future Improvements
- Add more dataset
- Improve accuracy using fine-tuning
- Add more genres

