# Proyek Akhir: Klasifikasi Gambar

## Dataset

The dataset consists of hand signs for rock, paper, and scissors. The dataset is divided into training and validation sets.

- Training Set: `rockpaperscissors/train`
- Validation Set: `rockpaperscissors/val`

[Dataset](https://github.com/dicodingacademy/assets/releases/tag/model-rockpaperscissors)

## Data Augmentation

Data augmentation is applied using the `ImageDataGenerator` from Keras to artificially increase the size of the training dataset.

## Model Architecture

The model is built using the Sequential API from TensorFlow's Keras. It consists of several convolutional and pooling layers, followed by dense layers.

## Training

The model is compiled using the Adam optimizer and categorical crossentropy loss. It is trained on the training set and validated on the validation set.

## Usage

1. Upload an image of a hand sign for rock, paper, or scissors to the Colab environment.
2. Execute the provided code to make predictions on the uploaded image.

## Dependencies

- TensorFlow
- Keras
- scikit-learn

## How to Run

1. Upload the provided code to a Google Colab environment.
2. Execute each cell sequentially to download the dataset, preprocess it, build the model, train the model, and make predictions on uploaded images.

## Biodata
 
- Name: Dike Ayu Wardani
- ID  : dikewarda


