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
  
### Producing results
Alternatively, you can open the notebook files directly in Jupyter Notebook or JupyterLab to execute the cells and visualize the results interactively. The random seed used is 42.


## License
This coursework is part of the IN3063 module at City, University of London, and is not licensed for public use. Please do not distribute.

## Contact
For questions, please contact the group members or reach out to the lecturer via the Moodle platform.
