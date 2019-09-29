# image_classification

This repository contains convolutional deep learning neural networks projects.
 
## Projects
* [Dog Breed Classifier](https://github.com/lorand1984/image_classification/tree/master/dog_breed_classifier): Build a convolutional neural network, creating a convolutional network from scratch as well as using transfer learning, with PyTorch in ordert to classify any image (even an image of a face) as a specific dog breed.
* [Image classification_with_tensor_flow](https://github.com/lorand1984/image_classification/tree/master/image_classification_with_tensor_flow): Build a convlutional neural network with Tensor flow that classifies up to 10 different classes. 

## Installation
1. Clone the repository
2. Download the latest version of [miniconda](https://docs.conda.io/en/latest/miniconda.html) that matches your system.
3. Create and Activate a conda environment.
 - __Linux__ or __Mac__:
 ```
  conda create -n "your_folder_name" python=3.6
  source activate "your_env_name"
 ```
 -  __Windows__:
  ```
  conda create --name "your_folder_name" python=3.6
  activate "your_env_name"
 ```
4. From the conda environment, install PyTorch and torchvision.
 - __Linux__ or __Mac__:
```
conda install pytorch torchvision -c pytorch
```
 -  __Windows__:
 ```
conda install pytorch -c pytorch
pip install torchvision
```
5. Install other dependencies using pip (See requirements text file including opencv and jupyter notebook).
  ```
pip install -r requirements.txt
  ```

