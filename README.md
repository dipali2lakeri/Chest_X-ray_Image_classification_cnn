# Chest X-ray Image Classification with CNN

This project implements a Convolutional Neural Network (CNN) for classifying chest X-ray images into multiple classes, aimed at assisting in the diagnosis of various lung diseases.


## Installation

1.Clone the repository

```bash
  git clone https://github.com/dipali2lakeri/Chest_X-ray_Image_classification_cnn.git
```
2.Navigate to the project directory

```bash
  cd Chest_X-ray_Image_classification_cnn

```

3.Install the required packages

```bash
  pip install -r requirements.txt

```
## Usage

Run the training script to start training the CNN model

```javascript
python train.py

```
You can also evaluate the model with
```javascript
python evaluate.py

```
## Dataset

The dataset consists of labeled chest X-ray images from [https://www.kaggle.com/datasets/sachinkumar413/covid-pneumonia-normal-chest-xray-images]. Make sure to place the dataset in the specified directory for proper access during training and evaluation.
## Model Architecture
The CNN architecture consists of multiple convolutional layers followed by max-pooling and fully connected layers,
optimized for image classification tasks.

![Chest X-ray Sample](https://github.com/dipali2lakeri/Chest_X-ray_Image_classification_cnn/blob/main/Screenshot%20(7).png )
## Results

The model's performance can be evaluated using accuracy metrics, and detailed results can be found in the results folder after training.
## Acknowledgements

 - [The Chest X-ray dataset ](https://www.kaggle.com/datasets/sachinkumar413/covid-pneumonia-normal-chest-xray-images)
