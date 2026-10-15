# ARTI 502 – Deep Learning Assignment 1

## MNIST Handwritten Digit Classification Using PyTorch

This assignment implements a fully connected Artificial Neural Network (ANN) using PyTorch to classify handwritten digits (0–9) from the MNIST dataset.

### Objectives
- Build and train a neural network using PyTorch.
- Evaluate model performance using loss and accuracy.
- Investigate the effects of learning rate, momentum, hidden layers, and neurons.
- Identify the best-performing configuration.

### Dataset
MNIST contains 60,000 training images and 10,000 test images. The dataset is downloaded automatically using PyTorch.

### Results
| Metric | Result |
|---|---|
| Baseline Test Accuracy | 97.51% |
| Best Validation Accuracy | 97.56% |
| Final Test Accuracy | **98.00%** |
| Final Test Loss | 0.0638 |

### How to Run
1. Install the required libraries:
   ```bash
   pip install torch torchvision numpy matplotlib pandas jupyter
   ```
2. Open `Assignment_1_DL.ipynb` in Jupyter Notebook or VS Code.
3. Run all cells in order. MNIST will be downloaded automatically if needed.

### Course Information
**Course:** ARTI 502 – Deep Learning  
**Assignment:** 1 – Training and Testing Neural Networks  
**Group:** 03  
**Academic Year:** 2026–2027
