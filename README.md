# CerdasProject
# Basic Handwritten Digit Recognition Model  

This project involves the creation and training of a handwritten digit recognition model using TensorFlow/Keras. It includes notebooks for model training, testing, and inference on new images.

## Obtaining Datasets

The project uses the MNIST dataset for training and testing the handwritten digit recognition model. To obtain the dataset:
1. You can directly access the MNIST dataset through the Keras library.
   - Example:
     ```python
     from tensorflow.keras.datasets import mnist
     
     (x_train, y_train), (x_test, y_test) = mnist.load_data()
     ```
2. Alternatively, you can download the MNIST dataset from authoritative sources such as [MNIST handwritten digit database](http://yann.lecun.com/exdb/mnist/) and follow the instructions provided on the website to acquire the dataset. Once downloaded, load the dataset into the notebook environment.

## Environment Setup for Local Execution

To execute the notebooks locally, follow these steps:

1. **Install Required Libraries**:
   - Ensure Python is installed on your machine. The code is written in Python 3.x.
   - Install required libraries using pip or conda.
     ```bash
     pip install tensorflow matplotlib ipywidgets
     ```
     Note: Additional libraries may be required for specific functionalities.

2. **Download or Clone the Project**:
   - Download or clone this repository to your local machine.
   - If using Git, use the following command:
     ```bash
     git clone https://github.com/yourusername/your-repository.git
     ```

3. **Access Notebooks**:
   - Open Jupyter Notebook or Google Colab or other tools.
   - Navigate to the downloaded/cloned project directory.
   - Launch the desired notebook (e.g., model_training.ipynb, image_inference.ipynb) by clicking on it.

4. **Notebook Execution**:
   - Follow the instructions within the notebooks to execute cells.
   - Upload new images for inference as per the provided instructions in the image_inference.ipynb notebook.

## Note
- Please ensure proper Python environment setup, including library dependencies, to execute the notebooks seamlessly.

