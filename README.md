# image-classifier-tm

# Fruit Classifier using Teachable Machine and Keras
This project uses a Teachable Machine image classification model to detect different fruits from images using Keras and TensorFlow in Python.

# Contents

- `keras_model.h5` — the trained model file
- `labels.txt` — list of class labels
- `classify_images.py` — script that loads the model and predicts images in a folder
- `test_images/` — folder of sample fruit images
- `README.md` — project overview

How It Works

1. Train a model using [Teachable Machine](https://teachablemachine.withgoogle.com/)
![Image](https://github.com/user-attachments/assets/d4ca274a-7d77-4df4-98a2-837b0e5b49bb)
3. Export the model in TensorFlow/Keras format
4. Use Python (`classify_images.py`) to:
   - Load the model
   - Preprocess each image
   - Predict the fruit
   - Print class and confidence
   - Show total count per fruit

# Run the Code

You can run this project in **Google Colab** or locally.

# Sample Output
![Image](https://github.com/user-attachments/assets/8fbe7f16-896d-44bb-8b67-4f709aa3125c)
![Image](https://github.com/user-attachments/assets/2e5509d2-36ea-4d3a-bc65-59fdd3824f82)
