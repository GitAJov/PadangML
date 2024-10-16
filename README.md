# PadangML

PadangML is a machine learning project designed to detect and classify Padang food based on images. The model can accurately identify nine different types of Padang dishes. This project is built using Python and various machine learning libraries, and the dataset is sourced from Kaggle.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Usage](#usage)
- [Results](#results)

## Project Overview

By training a convolutional neural network model on a dataset of Padang food images, the project can satisfactorily classify an image into one of the following nine popular padang dishes:

1. Ayam Goreng
2. Ayam Pop
3. Daging Rendang
4. Dendeng Batokok
5. Gulai Ikan
6. Gulai Tambusu
7. Gulai Tunjang
8. Telur Balado
9. Telur Dadar

## Dataset

The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/faldoae/padangfood/data).

## Usage

To use PadangML, open the Jupyter Notebook and follow the steps:

1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open `PadangML.ipynb`.
3. Follow the instructions within the notebook to preprocess the dataset, train the model, and run predictions.

## Results

The model reached 70% accuracy but tends to get confused between three types of "gulai." The notebook includes visualizations to help understand the model's performance and areas for improvement.
