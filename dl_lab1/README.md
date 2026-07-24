# Single Layer Perceptron for Binary Classification

This lab experiment implements a **Single Layer Perceptron** from scratch using Python.

## Objective

The objective of this experiment is to understand the working of an artificial neuron and implement the Perceptron Learning Algorithm for binary classification using the Banknote Authentication dataset. :contentReference[oaicite:0]{index=0}

## Features

- Exploratory Data Analysis (EDA)
- Data preprocessing and normalization
- Perceptron implementation from scratch
- Step Activation Function
- Model training using the Perceptron Learning Rule
- Performance evaluation
- Learning rate comparison
- Weight and bias evolution visualization
- Confusion matrix
- Additional implementation of OR, AND, NOT, and XOR logic gates

## Dataset

- **Dataset:** Banknote Authentication Dataset
- **Source:** UCI Machine Learning Repository
- **Samples:** 1372
- **Features:** 4 numerical features
- **Classes:** 2 (Authentic / Forged) :contentReference[oaicite:1]{index=1}

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Results

The perceptron successfully classifies linearly separable data and achieves high accuracy on the Banknote Authentication dataset. The experiment also demonstrates why a single-layer perceptron cannot solve the XOR problem, as XOR is not linearly separable. :contentReference[oaicite:2]{index=2}

## Repository Structure

```
├── DL_Lab1.ipynb
├── lab-1.pdf
└── README.md
```

## How to Run

1. Clone the repository.
2. Install the required Python libraries.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Run all cells sequentially.
