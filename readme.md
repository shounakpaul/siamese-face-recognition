# Siamese Network for Face Verification

This project implements a Siamese Network for face verification using TensorFlow and Keras. The network is trained to distinguish between positive and negative pairs of images.

## Requirements

- Python 3.6+
- TensorFlow 2.x
- OpenCV
- NumPy
- Matplotlib

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/siamese-face-verification.git
    cd siamese-face-verification
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Dataset

This project uses the Labeled Faces in the Wild (LFW) dataset. You can download the dataset from [here](http://vis-www.cs.umass.edu/lfw/lfw.tgz).

1. Download and extract the dataset:
    ```sh
    wget http://vis-www.cs.umass.edu/lfw/lfw.tgz
    tar -xvzf lfw.tgz
    ```

2. Move the extracted [`lfw`] folder to the project directory.


## Acknowledgments

- [LFW Dataset](http://vis-www.cs.umass.edu/lfw/)
- TensorFlow and Keras documentation

Feel free to contribute to this project by submitting issues or pull requests.