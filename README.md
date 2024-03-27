# Eye Detection using OpenCV

This repository contains a Jupyter Notebook that uses the OpenCV library to detect eyes in an image using a pre-trained Haar cascade classifier.

## Prerequisites

- Python 3.x
- OpenCV library
- Jupyter Notebook

## Installation

1. Clone the repository:
2. Install the required dependencies:
## Usage

1. Open the `Eye Detection.ipynb` notebook in Jupyter Notebook.

2. Make sure that the file paths in the notebook point to the correct locations for the `haarcascade_eye.xml` cascade classifier and the input image.

3. Run the cells in the notebook.

The notebook will process the specified image, detect faces, and then detect eyes within the detected faces. The result will display the image with detected faces highlighted by green rectangles and detected eyes highlighted by red rectangles.

## File Structure

- `Eye Detection.ipynb`: The Jupyter Notebook for eye detection.
- `cascades/haarcascade_eye.xml`: The pre-trained Haar cascade classifier for eye detection.
- `images/`: Directory for storing input images (if applicable).
- `README.md`: This file.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgments

- The OpenCV library and its contributors.
- The Haar cascade classifiers used in this project.
