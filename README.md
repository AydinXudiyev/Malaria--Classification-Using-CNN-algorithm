# Malaria Image Classification

This project focuses on classifying malaria-infected and uninfected cells using a deep learning model. The model is built using **TensorFlow** and trained on a dataset of malaria images. It is a binary classification problem where the goal is to classify images as either "infected" or "uninfected".

## Dataset

The dataset used in this project is a collection of malaria cell images, consisting of images labeled as "Parasitized" (infected) and "Uninfected". It is available on **Kaggle**.

- **Dataset Link**: [Malaria Dataset on Kaggle](https://www.kaggle.com/datasets)  
  (Make sure to download and extract the dataset for use in the project.)

## Project Structure

- **data/**: Folder containing the malaria images dataset.
- **model/**: Contains the architecture of the trained model.
- **notebooks/**: Jupyter notebooks for data exploration and model training.
- **src/**: Python scripts for model training and evaluation.

## Requirements

To run this project, you need to install the following dependencies:

- **TensorFlow** (version >= 2.0)

You can install TensorFlow using `pip`:

```bash
pip install tensorflow
