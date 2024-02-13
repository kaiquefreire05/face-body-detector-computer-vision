# Face and Body Detection with OpenCV

Author: [Kaíque Freire dos Santos]<br>
Date: February 13, 2024 

This repository contains a Jupyter notebook that demonstrates how to detect faces and bodies in images using the OpenCV library.

# Prerequisites

* Python 3
* OpenCV
* Google Colab (optional)

# How to use
1. Download the notebook face-body-detector-computer-vision.ipynb.
2. Open the notebook in Google Colab or your local environment.
3. Run notebook cells.

# What the notebook does

The notebook does the following:

* Face detection:
  * Read an image.
  * Loads a pre-trained face detector.
  * Converts the image to grayscale.
  * Detects faces in the image.
  * Draws rectangles around the detected faces.
* Body detection:
  * Read an image.
  * Carries a pre-trained body detector.
  * Converts the image to grayscale.
  * Detects bodies in the image.
  * Draws rectangles around detected bodies.

# Files

* Deteccao_de_Faces_e_Corpos.ipynb: The Jupyter notebook that contains the code.
* haarcascade_frontalface_default.xml: Pre-trained model for face detection.
* fullbody.xml: Pre-trained model for body detection.
* workplace-1245776_1920.jpg: Example image for face detection.
* people.jpg: Example image for body detection.

# Comments
* The pre-trained models haarcascade_frontalface_default.xml and fullbody.xml are included in this repository for your convenience. You can also download other pre-trained models from the OpenCV website: https://opencv.org/releases/.
* The notebook was tested on Google Colab. If you are running the notebook in your local environment, you may need to install the necessary libraries.

# License
This code is licensed under the MIT License.
