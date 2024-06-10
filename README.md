# Arrhythmia

## Overview
The Arrhythmia Detection project aims to identify arrhythmias from electrocardiogram (ECG) data using machine learning techniques. This project leverages a dataset of ECG recordings and applies various data processing and classification methods to accurately detect arrhythmias.

## Dataset
The [dataset](https://www.kaggle.com/datasets/shayanfazeli/heartbeat?fbclid=IwZXh0bgNhZW0CMTAAAR1pRZPcm87U8-pwhSyCEBs1GCCMbrDfytM3JVaHUsV_cvz7zxp8KBa74Bk_aem_AfOCxo65sCQ-020vDhvTc0R_0zKNHELlAZ0v4G73bvhqDs5OXQdNehXrsFuE2uoNrBB3VeGt318xUR4QAOd7iiDE) used in this project contains ECG recordings with labeled instances of different arrhythmia types. The data includes features extracted from ECG signals and the corresponding arrhythmia class.

## Project Structure
- **Data Preprocessing:** This step involves denoising, normalizing, resampling the dataset and splitting the data into training and testing sets.
- **Model Training:** Various machine learning models are trained and evaluated to identify the best performing model for arrhythmia detection.
- **Model Evaluation:** The models are evaluated using metrics such as accuracy, precision, recall, and F1-score to ensure robust performance.

## Dependencies
    Python 
    NumPy
    Pandas
    Scikit-learn
    Matplotlib


## Installation
To run this project locally, please follow these steps:
1. Clone the repository:
   
       git clone https://github.com/kSuroweczka/Arrhythmia
3. Open the `ArrhythmiaDetection.ipynb` notebook and run the cells to execute the project.

## Models
The following models were trained for arrhythmia detection:
- Convolutional Neural Network (CNN)
- Long Short-Term Memory (LSTM)
- Residual neural network (ResNet)

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
