
# Raspberry vs Strawberry Classifier – Teachable Machine + Keras

This project is a basic deep learning image classifier that distinguishes between **raspberries** and **strawberries**, trained using [Teachable Machine](https://teachablemachine.withgoogle.com/) and exported to Keras/TensorFlow for further experimentation in Google Colab.

## Project Overview

- I collected the data from resources like **Pinterest** and **Google**.
- Each class (`raspberries`, `strawberries`) was organized into **separate folders** to keep the dataset clean and well-labeled.
- I made sure that **test images are not inside the class folders**, so the model **won’t train on test images** and evaluation remains fair.
- The dataset contains a mix of images (e.g., different lighting, angles, backgrounds).
- As we can see from the results, the **model accuracy varies** depending on the complexity of the inputs.
- Of course, if I had **more images**, the model would likely become **more accurate and robust**.

## Dataset Structure

dataset/
├── raspberry/
│ ├── raspberry1.jpg
│ ├── ...
└── strawberry/
├── strawberry1.jpg
├── ...
test_images/
├── raspberry_test.jpg
├── strawberry_test.jpg

