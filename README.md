# EEG signal classification using PCA, ICA, LDA and support vector machines
 BM4152 - Biosignal Processing  Paper Implementation

 ![Project Banner](https://github.com/RavinduMPK/EEG-signal-classification-using-PCA--ICA--LDA-and-support-vector-machines/blob/main/Image/BSP%20Paper%20Implementation.png)  


This repository contains the code and resources for reproducing results from the paper titled **"EEG signal classification using PCA, ICA, LDA and support vector machines"** by Abdulhamit Subasi and M. Ismail Gursoy. This project applies various signal processing and classification techniques to EEG data for epileptic seizure detection.

## Project Structure

The repository is organized into the following folders:

1. **Dataset**: Contains the dataset used for the implementation.
   - [Download EEG Dataset](https://www.ukbonn.de/epileptologie/arbeitsgruppen/ag-lehnertz-neurophysik/downloads/)

2. **Wavelet_results**: Stores the results of a 5-level wavelet decomposition applied to EEG signals.

3. **Extracted_data**: Contains extracted features for each EEG signal. These features were used for training and testing the classification models.

## Description

This study explores the classification of EEG signals using **Discrete Wavelet Transform (DWT)** for signal decomposition, followed by **Principal Component Analysis (PCA)**, **Independent Component Analysis (ICA)**, and **Linear Discriminant Analysis (LDA)** for feature reduction. A **Support Vector Machine (SVM)** is then employed for the final classification. Key objectives of this project include feature extraction, dimensionality reduction, and performance analysis of different classification techniques.

## Code and Notebooks

The repository includes Jupyter notebooks (.ipynb files) where all programming was conducted. Each notebook corresponds to different phases of the study:
- Data preprocessing
- Wavelet decomposition and feature extraction
- Feature reduction using PCA, ICA, LDA
- SVM model training and testing

## Dependencies

To run the code, ensure the following Python libraries are installed:
- `numpy`
- `scipy`
- `pandas`
- `sklearn`
- `pywt` (for wavelet decomposition)
- `matplotlib` (for visualization)

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/eeg-signal-classification.git
   cd eeg-signal-classification
