# MNIST Handwritten Digits Classification
## Project Overview
The goal of this project is to train a simple feedforward neural network to classify images of handwritten digits (0-9) from the MNIST dataset. The model is trained on the training set and evaluated on the test set.

## Features
Data Loading: Uses torchvision to load the MNIST dataset and apply basic transformations.
Model Architecture: A simple feedforward neural network with multiple fully connected layers.
Training: The model is trained using a cross-entropy loss and the Adam optimizer.
Evaluation: The model's accuracy and loss are evaluated on the test set.


## Running the Project
Clone the repository:

`bash
git clone <repository_url>
cd <repository_name>`

Run the notebook:
Open the MNIST_Handwritten_Digits_STARTER.ipynb notebook and run the cells sequentially to train the model.

Results
After training, the model achieves the following results:

Training Accuracy: Varies per epoch (displayed during training)
Validation Accuracy: Varies per epoch (displayed during evaluation)
Final Model: The trained model is saved as checkpoint.pth.
Repository Structure
MNIST_Handwritten_Digits_STARTER.ipynb: The Jupyter notebook containing the code.
requirements.txt: A list of required Python packages.
checkpoint.pth: The trained model (generated after running the notebook).
License
This project is licensed under the MIT License.

