# Face Recognition and Comparison

This project uses Python to compare face  against other faces. It identifies potential face regions, generates a unique "face encoding" for each face, and then computes similarity scores using Euclidean Distance and Mean Squared Error (MSE).

## Features

* **Face Detection:** Locates faces within an image.
* **Face Encoding:** Generates a 128-dimensional vector (a "fingerprint") for each face.
* **Similarity Comparison:** Compares two face encodings using mathematical metrics.
* **Similarity Conclusion:** Provides a human-readable conclusion based on the comparison scores.

## Prerequisites

Before running the script, you need to install cmake and the following Python libraries. You can do this using pip:

* Go to: https://cmake.org

* Select the version of cmake corresponding to your machine
* Install it and reboot your machine 

```bash
pip install face_recognition numpy Pillow scipy scikit-image
