## Overview
This repository involves implementing neural networks from scratch using Python, developing deep learning models using PyTorch using MNIST, Fashion MNIST, and CIFAR-10 datasets, and writing a detailed report on the approaches taken.

### Author 
- Aram Gholikimilan

## Repository Structure
```
📂 IN3063_AI_Coursework
├── 📂 src                 # Code files for both Task 1 and Task 2
│   ├── Task_1_CIFAR10.ipynb      # Task 1 code for implementing NN from scratch
│   ├── Task_1_Mnist_&_FashionMnist_Datasets.ipynb      # Task 1 code for Mnist & Fasion Mnist
│   └── Task_2_CIFAR10_CNN.ipynb       # Task 2 code for PyTorch model
├── requirements.txt        # Required modules for the code to run
└── README.md              # Information on the coursework, setup, and instructions
```

## Getting Started

## Features
- Implementation of neural networks from scratch using Python.
- Development of convolutional neural networks using PyTorch.
- Application to benchmark datasets: MNIST, Fashion MNIST, and CIFAR-10.
- Includes interactive Jupyter notebooks for visualization and experimentation.

### Prerequisites
- Python 3.8+
- Libraries: `numpy`, `matplotlib`, `pytorch`, `scikit-learn`

### Setup Instructions
1. **Clone the repository**:
   ```sh
   git clone https://github.com/Aram-Milan/DeepLearning_MNIST_and_CIFAR10.git
   ```
2. **Navigate to the directory**:
   ```sh
   cd DeepLearning_MNIST_and_CIFAR10
   ```
3. **Install the dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

### Running the Code
- For Neural Network, run:
  ```sh
  jupyter nbconvert --execute --to notebook "src/Task_1_CIFAR10.ipynb" 
  jupyter nbconvert --execute --to notebook "src/Task_1_Mnist_&_FashionMnist_Datasets.ipynb"
  ```
- For CNN, run:
  ```sh
  jupyter nbconvert --execute --to notebook "src/Task_2_CIFAR10_CNN.ipynb"
  ```

## Results
- **Neural Network**: Achieved ~98% accuracy on MNIST and ~90% on Fashion MNIST datasets.
- **Convolutional Neural Network**: Achieved ~85% accuracy on the CIFAR-10 dataset.
- Visualizations include training/validation loss curves, accuracy plots, and sample predictions.

### Producing results
Alternatively, you can open the notebook files directly in Jupyter Notebook or JupyterLab to execute the cells and visualize the results interactively. The random seed used is 42.

## Citation
If you use this work in your research or projects, please cite it as:

Aram Gholikimilan. "DeepLearning_MNIST_and_CIFAR10". Version 1.0.0, 2024. [GitHub Repository](https://github.com/Aram-Milan/DeepLearning_MNIST_and_CIFAR10).

For detailed citation information, see the [CITATION.cff](CITATION.cff) file.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, feel free to contact:
- **Author**: Aram Gholikimilan
- **Email**: gholikimilan@hotmail.com

