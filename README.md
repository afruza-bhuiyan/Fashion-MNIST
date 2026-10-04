# Fashion MNIST Image Classification

A machine learning project using a neural network to classify images from the Fashion MNIST dataset into different categories of clothing and footwear.

## Project Overview

This project explores image classification using Python, TensorFlow and Keras. A neural network was trained on the Fashion MNIST dataset, with different model configurations tested to compare their performance.

The project covers:

* Loading and preprocessing the Fashion MNIST dataset
* Building a neural network using TensorFlow/Keras
* Training and evaluating the model
* Comparing different model configurations
* Analysing model performance using accuracy and loss
* Evaluating predictions using a confusion matrix
* Visualising example predictions

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Google Colab
* Jupyter Notebook

## Dataset

The Fashion MNIST dataset contains 70,000 grayscale images across 10 categories of clothing and footwear.

The classes are:

1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

Each image is 28 × 28 pixels.

## Approach

The images were preprocessed and normalised before being used to train the neural network.

Several model configurations were tested to investigate how changes to the network affected its performance. The final configuration was then trained and evaluated using previously unseen test data.

Model performance was examined using:

* Training and validation accuracy
* Training and validation loss
* Confusion matrix
* Example predictions
* Configuration comparisons

## Results

The experiments demonstrated that a neural network can successfully classify Fashion MNIST images into the ten clothing categories.

The notebook contains the full training process, model configurations, evaluation results and visualisations.

## Visualisations

### Confusion Matrix

The confusion matrix shows how the model's predictions compare with the actual classes in the test dataset.

![Confusion Matrix](images/confusion_matrix.png)

### Example Predictions

Example predictions demonstrate how the trained model classifies individual Fashion MNIST images.

![Example Predictions](images/example_prediction.png)

### Configuration Comparison

Different neural network configurations were compared to examine their effect on model performance.

![Configuration Comparison](images/configuration_comparison.png)

### Final Training Results

Training and validation accuracy and loss are visualised to show how the final model performed during training.

![Final Training Results](images/final_training.png)

## Project Structure

```text
Fashion-MNIST-Classification/
│
├── Fashion_MNIST_Classification.ipynb
├── README.md
└── images/
    ├── confusion-matrix.png
    ├── example-prediction.png
    ├── configuration-comparison.png
    └── final-training.png
```

## How to Run

The notebook was developed and tested using Google Colab.

To run the project:

1. Open the `.ipynb` notebook.
2. Open it in Google Colab.
3. Run the notebook cells from top to bottom.
4. The Fashion MNIST dataset will be loaded and processed by the notebook.

## What I Learned

This project provided practical experience with:

* Python for machine learning
* TensorFlow and Keras
* Neural network development
* Image classification
* Data preprocessing
* Model evaluation
* Comparing machine learning configurations
* Interpreting confusion matrices and model predictions
* Using Google Colab and Jupyter notebooks
