# MNIST Digit Classification using PyTorch

This project implements a Convolutional Neural Network (CNN) for classifying handwritten digits from the MNIST dataset. It achieves **99.03% accuracy** on the test set.

## Features
- Uses PyTorch for building and training the model.
- Implements a CNN with two convolutional layers and fully connected layers.
- Visualizes sample predictions with matplotlib.

## Requirements
To run this project, you'll need to install the following libraries:
- Python 3.10+ (ensure it's installed on your system)
- PyTorch
- Torchvision
- Matplotlib

## Setup Instructions
1. Clone this repository:
   bash
   git clone https://github.com/your-username/mnist-digit-classification.git
   cd mnist-digit-classification
   ## Setup Instructions
1. Create a virtual environment :
   bash
   python -m venv venv
   source venv/bin/activate   # On Linux/macOS
   venv\\Scripts\\activate      # On Windows


2. Create a virtual environment (optional but recommended):
   bash
   python -m venv venv
   source venv/bin/activate   # On Linux/macOS
   venv\Scripts\activate      # On Windows
   

3. Install the required libraries:
   bash
   pip install torch torchvision matplotlib
   
   pip install -r requirements.txt
s

4. Run the script:
   bash
   python main.py
   

## Output
- Training loss per epoch.
- Test accuracy.
- Visualization of predictions on test data.

## File Details
- main.p: Main script for training, evaluating, and visualizing the model.
- `mnist_model.pth`: Saved PyTorch model file.
- `README.md`: Documentation.

## Results
- Test Accuracy: 99.03%
- Sample Predictions:
  [Sample Predictions](example_predictions.png) 


## License
This project is open-source under the MIT License.

