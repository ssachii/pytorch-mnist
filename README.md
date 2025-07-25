# pytorch-mnist
Neural Network for Handwritten Digit Classification

### MNIST Digit Recognizer in PyTorch 🧠
`handwritten_digit_recognition_io.ipynb`

As part of the **PESU I/O Slot 16: Computer Vision and Intro to Neural Networks**
The model's performance is evaluated using training plots, a confusion matrix, and custom handwritten images for testing.

#### Key Features

* **MLP Model**: Implements a simple Multi-Layer Perceptron (MLP) for classification.
* **Visual Analysis**: Plots training & validation loss and accuracy curves to diagnose model fit.
* **In-Depth Evaluation**: Generates a confusion matrix and classification report to see where the model succeeds and fails.
* **Testing**: Includes a section to upload and test your own handwritten digit images.

#### How to Run

1.  Open the `.ipynb` file in **Google Colab**.
2.  Set the runtime to **T4 GPU** (`Runtime -> Change runtime type`).
3.  Run all cells sequentially.

#### Stack

Python, PyTorch, Scikit-learn, Matplotlib, Seaborn.       

<br>
<br>
<br>

`mnist_cnn_version.ipynb`

GPU-accelerated version using CNN with data augmentation, learning rate scheduling, and comprehensive performance analysis.
