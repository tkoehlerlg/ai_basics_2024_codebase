# Clickbait Detection Using AI

This project explores the use of Artificial Intelligence techniques to detect clickbait in article headlines. It implements and compares two main approaches: Recurrent Neural Networks (RNNs) and Convolutional Neural Networks (CNNs).

## Repository Structure

The repository contains the following main files:

- `rnn.ipynb`: Google Colab notebook implementing and analyzing the RNN approach for clickbait detection.
- `cnn.ipynb`: Google Colab notebook implementing and analyzing the CNN approach for clickbait detection.

## Getting Started

This project is designed to run in Google Colab, which provides a free, cloud-based Jupyter notebook environment with GPU support.

To run the project:

1. Ensure you have a Google account to access Google Colab.
2. Open the desired notebook (`rnn.ipynb` or `cnn.ipynb`) in Google Colab:
   - Go to https://colab.research.google.com
   - Click on 'File' > 'Open notebook'
   - Select the 'GitHub' tab
   - Enter the URL of this repository
   - Choose the notebook you want to run

## Running the Models

1. Once the notebook is open in Google Colab, please add the Dataset file as described in the **Dataset** Section.
2. You can now run the cells in order.
3. If prompted, allow the notebook to access your Google Drive (for saving outputs).
4. The notebooks are set up to use Google Colab's GPU. To ensure it's enabled:
   - Go to 'Runtime' > 'Change runtime type'
   - Set 'Hardware accelerator' to 'GPU'
   - Click 'Save'

Note: The notebooks are designed to be self-contained, including preprocessing, model definition, training, and evaluation.

## Dataset

This project uses a dataset of over 32,000 rated article headers. The dataset is loaded within each notebook from a local URL. Please upload the clickbait_data.csv file to colab in order to access the dataset.

## Results

The notebooks include visualizations of training progress and final model performance. In my AI Basics.pdf file I compared the RNN and CNN approaches in terms of accuracy and training efficiency.

For the high-level overview of the project, its methodology, and conclusions, please also refer to the project description (AI Basics.pdf).
