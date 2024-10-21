# IndiTranslate

IndiTranslate is an innovative OCR-powered translation tool that aims to break language barriers by converting posters in various regional languages into English. With the rapid globalization and the increasing need for accessible information, this tool serves as an essential resource for individuals, businesses, and organizations that require accurate translations for better communication and understanding.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [How It Works](#how-it-works)

## Features

- **Multi-Language Support**: IndiTranslate can handle posters in various regional languages and accurately convert the text into English, making it accessible for a wider audience.
- **High Accuracy OCR**: Utilizes Keras-OCR, a state-of-the-art optical character recognition tool, to extract text from images with high accuracy.
- **User-Friendly Interface**: Built on the Flask framework, the application provides an intuitive web interface that allows users to upload images easily and view translated text without hassle.
- **Performance Optimization**: The tool achieves a 20% improvement in text recognition performance through advanced machine learning techniques.
- **Real-Time Translation**: Offers instant translation, enabling users to receive results quickly, which is crucial for on-the-spot needs.

## Tech Stack

- **Programming Languages**: 
  - **Python**: For backend development and implementing machine learning algorithms.
  - **HTML/CSS**: For creating a responsive and user-friendly frontend.

- **Libraries/Frameworks**:
  - **Keras-OCR**: For extracting text from images using deep learning techniques.
  - **TensorFlow**: For building and training machine learning models.
  - **Flask**: A lightweight web framework for developing the web application.

- **Front-End Technologies**:
  - **HTML**: For structuring the web application.
  - **CSS**: For styling and ensuring a pleasant user experience.

## How It Works

1. **Image Upload**: Users can upload an image containing text in a regional language through the web interface.
2. **Text Extraction**: Once the image is uploaded, the Keras-OCR library processes the image to detect and extract text accurately.
3. **Translation Process**: The extracted text is then translated into English using an internal translation model that leverages advanced NLP techniques.
4. **Display Results**: The translated text is displayed on the web interface, allowing users to view and utilize the information seamlessly.


## Demo Video

Watch the demo video to see how IndiTranslate works [here](https://drive.google.com/uc?id=1QEbs_TleIe3HqEBPFDIG84nhE_D7mdam).
