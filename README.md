# Eye for Blind
**Problem statement:** In this capstone project, you need to create a deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism on Flickr8K dataset. 
This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library. 
This problem statement is an application of both deep learning and natural language processing. The features of an image will be extracted by a CNN-based encoder and this will be decoded by an RNN model.

The project is an extended application of [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention paper](https://arxiv.org/abs/1502.03044).



## Table of Contents
* [General Info](#general-information)
* [Model Architecture](#model-architecture)
* [Technologies Used](#technologies-used)

## General Information

The dataset is taken from the Kaggle website and it consists of sentence-based image descriptions having a list of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events of the image.

**Dataset link:** [https://www.kaggle.com/datasets/adityajn105/flickr8k]

## Model Architecture

![74751f7e-5e91-41df-9c1b-c5a3b76c9ea0-summary](https://github.com/user-attachments/assets/48032586-daca-4755-938c-5180d806971f)


## Technologies Used
- tensorflow
- keras
- gTTS
- CNN
- RNN
- Model subclassing
- Attention model
- Encoder Decoder architecture

## Contact
Created by [@shootingStar10](https://github.com/shootingStar10) - feel free to contact me!
