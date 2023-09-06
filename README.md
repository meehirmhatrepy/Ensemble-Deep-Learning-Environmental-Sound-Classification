# ESC-50-DeepLearning

## Overview
This repository contains a Jupyter Notebook (`esc-50-deep-learning.ipynb`) that demonstrates the process of training deep learning models for audio classification using the ESC-50 dataset. The ESC-50 dataset consists of 2000 environmental audio recordings categorized into 50 different classes. The notebook covers data preprocessing, model building, training, evaluation, and model comparison.

## Dataset
To run the notebook successfully, you will need to download the ESC-50 dataset from the official repository: [ESC-50 Dataset](https://github.com/karolpiczak/ESC-50). Make sure to set the dataset path variable within the code to the location where you have stored the dataset on your local machine.

## Libraries Used
The following Python libraries are used in this project:
- NumPy
- Matplotlib
- Librosa
- Scikit-learn
- TensorFlow
- Keras
- Torchaudio
- Scikit-image

Make sure to have these libraries installed in your Python environment to execute the notebook.

## Usage
1. Download the ESC-50 dataset from the provided link and set the dataset path variable in the Jupyter Notebook to the location where you have stored the dataset.

2. Open the `esc-50-deep-learning.ipynb` notebook in a Jupyter Notebook environment.

3. Execute the notebook cells sequentially to perform the following tasks:
   - Data preprocessing and feature extraction.
   - Building and training deep learning models (VGG16, VGG19, ResNet152, Custom CNN).
   - Model evaluation using metrics like accuracy, mean squared error, precision, recall, and F1-score.
   - Comparing the performance of different models.

4. Analyze the results and insights provided in the notebook to gain a better understanding of deep learning-based audio classification.

## Acknowledgments
- The ESC-50 dataset was created by Karol J. Piczak and can be found at [ESC-50 Dataset](https://github.com/karolpiczak/ESC-50).
- This project is for educational purposes and serves as a guide to working with audio data and deep learning models.

Feel free to reach out if you have any questions or need further assistance with running the notebook or understanding the code.

Happy learning!
