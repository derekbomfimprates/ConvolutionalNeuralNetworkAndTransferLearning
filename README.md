# ConvolutionalNeuralNetworkAndTransferLearning


This project involves applying two image classification models to a dataset of product and background images. The goal is to compare the performance of:

1. A **Convolutional Neural Network (CNN)** built from scratch.
2. A **Transfer Learning model**, using a pre-trained network.

The dataset is categorized by class, with each product having its own class, while background images are labeled separately. The task requires handling class imbalance, applying fine-tuning, and thoroughly documenting the code and process.

## Dataset

The dataset can be found at the following [link](https://drive.google.com/drive/folders/1QGOx4H_bQHCdHmmOu2yt8mbmgqe8tMPq?usp=sharing).

- **Class 1**: Product 1
- **Class 2**: Product 2
- **Class 3**: Product 3, and so forth...
- **Background**: Background images (this class may be used for additional preprocessing).

## Project Structure

```bash
.
├── data/                   # Folder where the dataset will be placed
├── models/                 # Folder to save trained models
├── notebooks/              # Jupyter notebooks (if any)
├── src/                    # Python scripts for model building and training
│   ├── cnn_model.py        # CNN model code
│   ├── transfer_learning.py # Transfer learning model code
│   └── utils.py            # Helper functions (e.g., data loading, preprocessing)
├── README.md               # Project documentation (this file)
└── requirements.txt        # Required libraries and dependencies

pip install -r requirements.txt

This README format is designed to be clear and concise, providing an overview of the project while guiding the user on how to run and understand the code. Make sure to adjust any file paths or specific instructions based on your actual implementation.
