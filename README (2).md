
# Implementing a Fully-Connected Artificial Neural Network for Regression using MERL brdf DataSet

Group Members: Naga Sai Akhila,
Harsha Ponnada, Pranav Polisetti





## This script trains a neural network using a tanh activation function. It is designed for a regression task with a dataset containing input features and corresponding output values.
## Requirements
- Python (>=3.6)
- NumPy
- Matplotlib
- VSCode
- Google Colab

## Usage

1. Download the BRDF zip file and use VSCode and WSL terminal to generate the output.txt using C++ code from dark red binary file.

2. Upload this output.txt to the google colab and run the ProjectNN_AI.ipynb 




## Hyperparameters
Adjust the hyperparameters in the script based on your specific requirements. Explanation of hyperparameters:

Learning Rate: 0.001
Epochs: 10000
Batch Size: 64
Input Size: 7
Hidden Layer Sizes: 10, 5
Output Size: 3
## Results

The script will generate plots illustrating the training, test, and validation errors over epochs. The final weights of the neural network will be saved to final_weights_TanH.txt.
## Early Stopping and Learning Rate Adjustment

Early stopping is applied if the validation error does not improve for 20 epochs.
Learning rate is reduced by 10% every 100 epochs if the validation error increases.
## Files

ProjectNN_AI.ipynb: The main training script.
final_weights_TanH.txt: Text file containing the final weights of the neural network.
output.txt: Input and output data file.
Error Images: ErrorImage_Tanh, ErrorImage_Relu, ErrorImage_Sigmoid

