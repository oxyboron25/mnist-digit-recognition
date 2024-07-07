# MNIST Digit Recognition

This repository contains code for training and evaluating a digit recognition model using the MNIST dataset.

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib

## Installation

Clone the repository:

```bash
git clone https://github.com/oxyboron25/mnist-digit-recognition.git
cd mnist-digit-recognition
```

Install dependencies using pip:

```bash
pip install -r requirements.txt
```

## Usage

### Training the Model

To train the model, run:

```bash
python train.py
```

This will train the digit recognition model using the MNIST dataset.

### Evaluating the Model

To evaluate the model on the test set, run:

```bash
python evaluate.py
```

This will evaluate the accuracy of the trained model on the MNIST test dataset.

### Predicting Digit Images

To predict digits from custom images, use:

```bash
python predict.py path_to_image
```

Replace `path_to_image` with the path to the image file you want to predict.

## Structure

- `data/`: Contains the MNIST dataset (automatically downloaded if not present).
- `models/`: Saved models after training.
- `train.py`: Script for training the digit recognition model.
- `evaluate.py`: Script for evaluating the model's accuracy.
- `predict.py`: Script for predicting digits from custom images.
