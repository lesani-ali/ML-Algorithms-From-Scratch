# ML-Algorithms-From-Scratch

This repository contains implementations of various machine learning algorithms from scratch. The goal is to provide a clear and educational view of how these algorithms work under the hood without relying on high-level libraries like scikit-learn, PyTorch, and etc.

## Implemented Algorithms

1. Logistic Regression
2. (To be added) Linear Regression
3. (To be added) Multi-Layer Perceptron (MLP)

## Optimizers

1. Stochastic Gradient Descent (SGD)
2. (To be added) Other optimizers

## Dataset

The MNIST dataset is used to test the implementations of the algorithms. MNIST is a dataset of handwritten digits and is widely used for training and testing in the field of machine learning.


## Project Structure
```
ML-Algorithms-From-Scratch/
├── classes/                     # Directory containing class implementations
│   ├── __init__.py
│   ├── LogisticRegression.py    # Implementation of Logistic Regression
│   ├── SGD.py                   # Implementation of Stochastic Gradient Descent Optimizer
│   ├── utils.py                 # Utility functions (gen_batches, compute_accuracy, load_data, train, etc)
├── main.ipynb                   # Notebook demonstrating the use of algorithms
├── .gitignore                   # Git ignore file
├── environment.yml              # Python dependencies
└── README.md                    # Project README file
```

## Cloning Repository from GitHub
Use this command to clone the repository from GitHub: <br>
`git clone git@github.com:lesani-ali/ML-Algorithms-From-Scratch.git`<br> 


## Environment Setup
Please follow these steps to set up the working environment:
1. Install Miniconda (use terminal to execute these commands):
    - Create a Directory:<br>
    `mkdir -p ~/miniconda3`
    - Download the Miniconda Installer:<br>
    `curl https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.sh -o ~/miniconda3/miniconda.sh`
    - Run the Miniconda Installer:<br>
    `bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3`
    - Remove the Installer Script:<br>
    `rm -rf ~/miniconda3/miniconda.sh`
    - Add to path:<br>
    `source ~/miniconda3/bin/activate`
    - Initialize for bash and zsh shells:<br>
    `~/miniconda3/bin/conda init bash`<br>
    and <br>
    `~/miniconda3/bin/conda init zsh`

    For more information visit [Miniconda](https://docs.anaconda.com/miniconda/) website.

2. Create conda environment and install all packages (I used "data_collection" as a name for my environment): <br>
`conda env create -f environment.yml`

3. Activate the environment: <br>
`conda activate ML`

## Future Work
- Implement Linear Regression from scratch.
- Implement Multi-Layer Perceptron (MLP) from scratch.
- Add other optimizers like Adam, RMSprop, etc.
- Improve the documentation of code.

## Acknowledgements
- The MNIST dataset is provided by Yann LeCun and can be found [here](http://yann.lecun.com/exdb/mnist/).
- This project was inspired by the desire to understand and implement machine learning algorithms from scratch.
