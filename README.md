# Dog Breed Classifier Project for Udacity Machine Learning Engineering Nanodedree 

## Project overview
This is dog breed classifier project for Udacity's Machine Learning Engineering Nanodegree program. In this project, I build and train **Convolutional Neural Network (CNN)** as image classifier in **Jupiter Notebook** using **PyTorch**. This code must be able to:

* Detect whether an image contains a dog or human, and distinguish between the two.
* If given an image of a dog, the model predicts its breed with at least 60% accuracy. Random chance is less than 1% since there are 133 dog breeds (classes) in the dataset.
* If given an image of a human, the model identifies the dog breeds the person most resembles.

After building a model from scratch and exploring different CNN architectures, I build the final algorithm on pre-trained VGG16 model. Using **learning transfer** I added and trained two final layers on top of pretrained CNN to do the final classification of dog breeds.

## Prerequisites
The code is **Python** in a **Jupyter Notebook** and it uses:

* [PyTorch](https://https://pytorch.org/)
* [Matplotlib](https://matplotlib.org/)
* [NumPy](http://www.numpy.org/)

You can install everything you need to run this project with [Anaconda](https://www.anaconda.com/).


## Run the Code
Navigate to the cloned directories location and start jupyter notebook with dog_app.ipynb

`jupyter notebook dog_app.ipynb`
