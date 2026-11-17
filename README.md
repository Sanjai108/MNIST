# MNIST


This project uses neural networks to classify grayscale images of handwritten digits into ten classes (0–9). The notebook compares model configurations and training choices, including epoch count, batch size, hidden-layer size, and activation functions.

## Dataset

The notebook loads MNIST through TensorFlow/Keras. It contains 70,000 labeled images:

- 60,000 training images
- 10,000 test images
- Each image is 28 × 28 pixels, with a digit label from 0 to 9

The training data is further split into training and validation sets for model comparison.

## Repository contents

| File | Description |
|---|---|
| `MNIST.ipynb` | Loads and explores MNIST, trains neural-network configurations, and compares their performance |

## Requirements

Use Python 3 with Jupyter Notebook or JupyterLab. Install the required packages with:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter
```

## Run the notebook

1. Open `MNIST.ipynb` in Jupyter Notebook or JupyterLab.
2. Run the cells in order. The dataset is downloaded through `keras.datasets.mnist` if it is not already available locally.

Model results and training times may vary depending on your hardware and software environment.
