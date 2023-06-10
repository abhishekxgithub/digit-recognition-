# MNIST Image Classification with TensorFlow

This repository contains a Python script for performing image classification on the MNIST dataset using TensorFlow. The script trains a neural network model on the MNIST handwritten digit dataset and then makes predictions on custom images.

## Prerequisites

Make sure you have the following dependencies installed:

- Python 3
- TensorFlow
- NumPy
- OpenCV (cv2)
- Matplotlib

You can install the required Python packages using `pip` with the following command:

```
pip install tensorflow numpy opencv-python matplotlib
```

## Getting Started

1. Clone this repository to your local machine or download the code files.

2. Ensure that you have the MNIST dataset available. The script uses the TensorFlow `mnist` dataset, which can be loaded using the `tf.keras.datasets.mnist` module. If you don't have the dataset, it will be automatically downloaded when you run the script for the first time.

3. (Optional) If you want to make predictions on your own custom images, create a directory named `images` in the same location as the script and place your PNG images in it. Make sure the images are named `1.png`, `2.png`, `3.png`, and `4.png`.

4. Run the script `mnist_classification.py` using the following command:

```
python mnist_classification.py
```

5. The script will train a neural network model on the MNIST dataset and display the accuracy and loss on the test set. After that, it will make predictions on the custom images (if available) and display the predicted digit along with the corresponding image.

## Customization

Feel free to modify the code according to your needs. You can experiment with different neural network architectures, optimization algorithms, loss functions, or hyperparameters to improve the model's performance.

## License

This code is provided under the [MIT License](LICENSE).

Please note that this is a sample README file, and you may need to customize it further based on your specific requirements.
