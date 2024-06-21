# Automated Research Paper Classification

## Overview
This project aims to automate the classification of research papers into predefined categories using natural language processing (NLP) techniques. It leverages state-of-the-art models like SciBERT, augmented with BiLSTM layers, and custom data preprocessing and augmentation strategies to enhance model performance. This solution can significantly aid academic database management, systematic review processes, and the categorization of scholarly articles for researchers and publishers.

## Files Description

### Notebooks

- `Augmentation.ipynb`
  - Description: Demonstrates data augmentation techniques specifically designed for textual data, enhancing the diversity of our training dataset to improve model robustness against varied linguistic expressions found in research papers.

- `Data_preprocessing.ipynb`
  - Description: Outlines the preprocessing steps applied to the dataset of research papers, including text cleaning, tokenization, and normalization, preparing data for efficient model training.

- `bilstm_scibert.ipynb`
  - Description: Combines the capabilities of SciBERT, an NLP model pre-trained on scientific literature, with BiLSTM layers to capture both the contextual and sequential nuances in research papers, aiming at improving classification accuracy.

- `linear_layer_after_scibert.ipynb`
  - Description: Explores the impact of adding linear layers following SciBERT embeddings, fine-tuning the model to tailor it to the specific classification needs of our dataset.

- `main_model_training.ipynb`
  - Description: The core notebook that orchestrates the model training process, from loading preprocessed data to training and validating the model, culminating in the evaluation of its performance on a test set.

- `weight_tensor_custom_loss.ipynb`
  - Description: Implements a custom loss function that leverages a weight tensor to address class imbalance in the dataset, ensuring a fair and effective learning process.

### Other Files

- `README.md`
  - Provides an overview of the project, including detailed descriptions of all included files and instructions for their use.



```bash
pip install -r requirements.txt
