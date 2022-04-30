# DL based toxic comments classification 🤬 [![Project Status: Active](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active) [![](https://img.shields.io/badge/Prateek-Ralhan-brightgreen.svg?colorB=ff0000)](https://prateekralhan.github.io/)
Deep learning based classification model for classifying toxic comments built on top of tensorflow

## Installation:
* Simply run the command ***pip install -r requirements.txt*** to install the necessary dependencies.
* In case you need to use your GPU for computation, ensure that you have the right CUDA drivers and CUDNN installed. You can read more about this [here.](https://www.tensorflow.org/install/gpu)

## Dataset:
The dataset has been taken from [here.](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data)

## Usage:
1. Download the datasets from the above mentioned link and unzip them.
2. Clone this repository and create a directory named `dataset` in the same directory as the cloned repo. Your directory structure should look like this:

![2](https://user-images.githubusercontent.com/29462447/166077220-af35f16c-75f3-48e6-af52-3ef711dc9041.png)

3. Navigate to the `notebooks` directory and simply run the command: 
```
jupyter notebook
```
4. This will launch the jupyter notebook (.ipynb file) in your web browser. Simply hit `Shift+Enter` to execute all the cells. Your generated model will be saved in `models` directory.


## Results 

#### Model Summary:
![1](https://user-images.githubusercontent.com/29462447/166076707-f3e590da-3d37-4fe7-a352-103845274b24.png)

#### Training,Validation Loss:
![3](https://user-images.githubusercontent.com/29462447/166093355-f394e7fd-d59a-4138-ac58-d192727c3bdc.png)

#### Evaluation metrics:
![4](https://user-images.githubusercontent.com/29462447/166093357-89578666-84b1-4775-8c26-c858cf9dc0f1.png)

*(Hyperparameters tuning needed for refining the results and improving the metrics.)*




