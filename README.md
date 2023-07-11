# Sacroiliac Detection in Medical Images
This repository contains a Python code implementation for the detection of sacroiliac regions in medical images. The code utilizes deep learning and object detection techniques to identify and visualize the regions of interest in the images.

Environment and Tools
The code was developed and tested in the Google Colab environment, a cloud-based platform that provides an interactive notebook environment for Python development. The main libraries used in the code include:

TensorFlow: A popular machine learning and AI library used for training and inferring object detection models.
Keras: A high-level library built on top of TensorFlow, which provides a simplified interface for creating and training deep learning models.
OpenCV: A computer vision library that provides functions for image processing and manipulation.
PIL (Python Imaging Library): An image processing library used for opening and saving images in different formats.
NumPy: A library for array manipulation and numerical computations in Python.
How to Use
Follow the steps below to use the code:

Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/sacroiliac-detection.git
Open the main.ipynb file in the Google Colab environment.

Execute the code cells sequentially to load the libraries, mount Google Drive, install dependencies, and run the sacroiliac detection code.

Analyze the obtained results and visualized detections in the test images.

Files and Directories
main.ipynb: The main file that contains the complete code for sacroiliac detection in medical images.

Imagem.py: A Python module containing the definition of the Imagem class to represent the images and their relevant information.

classes.csv: A CSV file containing the class information, including labels and identifiers.

annotation.csv: A CSV file containing the annotation information of the images, including image paths, coordinates of regions of interest (ROIs), and corresponding classes.

snapshots/: A directory that stores snapshots of the trained model during the training process.

Dependencies
The code has the following dependencies:

TensorFlow
Keras
OpenCV
PIL
NumPy
The dependencies can be installed using the !pip install command in the Google Colab environment.

Notes
This code is provided for educational purposes only and does not substitute professional medical analysis. Always consult a qualified healthcare professional for an accurate and reliable diagnosis.

The performance of the trained model may vary depending on the data used and the training settings. It is recommended to adjust the parameters and perform proper validation before using the model in a production environment.

References
TensorFlow: https://www.tensorflow.org/
Keras: https://keras.io/
OpenCV: https://opencv.org/
PIL (Python Imaging Library): https://pillow.readthedocs.io/
NumPy: https://numpy.org/
Author
This code was developed by Gabriel Rosa Arcangelo and is part of the project for the Applications of Artificial Intelligence in Medical Images course. For more information, please contact gabriel.arcangelo@usp.br.

Special thanks to Paulo Mazzoncini for the guidance during the development of this project.
