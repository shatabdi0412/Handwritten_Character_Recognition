# Handwritten Character Recognition
This project is the part of my PG Diploma in Artificil Intelligence and Machine Learning Course from NIT Warangal (jointly with Edureka)

# Aim ofthe Project

The aim of this project is to automatically convert handwritten text into machine encoded text.

# Learning Outcome

1. Implementation of Convolutional Neural Network to extract features from images.
2. Implementation  of  Recurrent  Neural  Network  (GRU,  LSTM,  Bi-LSTM,  etc.) to process sequential data.
3. Preparation and preprocessing of image data.
4. Preparation and preprocessing of image data.
5. Development, error analysis,and deep learning model improvement.

# Problem Statement

A medical company needs to take handwritten prescription and retrieve the text from it. To do this manually,it will require a lot of timeand lots of cost to the company.So, the company wants to automate this task.Youneed to create a neural network model tha twill take images as input, read the text images,and convert it into digital text. To solve this problem, you need to create a CNN LSTM model.

# Strategy

The project has 4major components:
1. Preprocess image and text data.
2. Implementation of CNN layers to extract features.
3. Implementation of RNN(Bi-LSTM) layers to the sequence model.
4. CTC_loss and CTC_decode.
- To learn more about CTC,refer to the following
  :https://towardsdatascience.com/intuitively-understanding-connectionist-temporal-classification-3797e43a86c
  - ctc_batch_cost: https://www.tensorflow.org/api_docs/python/tf/keras/backend/ctc_batch_cost
  - ctc_decode: https://www.tensorflow.org/api_docs/python/tf/keras/backend/ctc_decode

# Dataset Description

Dataset: IAM Dataset
We will  be  using the IAM  dataset  for  training  and  testing  your  model. We  will  use  the  words subset of the dataset, in  which each image contains a word. The dataset contains over 8000 images and their digital text.
This is a sample from text file,
a01-000u-01-03 ok 156 1400 937 294 59 NN Labour
where, a01-000u-01-03: image location+ image id
Labour: actual word
Image file contains one word in each image
![image](https://github.com/shatabdi0412/Handwritten_Character_Recognition/assets/134500115/4038633c-aa5a-47fb-b91f-f8877be05bb4)

