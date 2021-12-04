# Pneumonia_detection
Pneumonia Detection with Python

## Introduction to Pneumonia Detection

Pneumonia is an infectious and fatal respiratory disease caused by bacteria, fungi, or a virus that infects human lung air sacs with a load full of fluid or pus.

Chest x-rays are the common method used to diagnose pneumonia and it takes a medical expert to assess the result of the x-ray. The troublesome method of detecting pneumonia leads to loss of life due to improper diagnosis and treatment.

With the emerging computing power, the development of an automatic pneumonia detection and disease treatment system is now possible, especially if the patient is in a remote area and medical services are limited.

## Machine Learning Project on Pneumonia Detection with Python

In this section, I will take you through a Machine Learning Project on Pneumonia Detection with Python programming language. I will use the Fastai library in Python for the task of Pneumonia Detection.
**Now let’s get started with this task by importing the necessary Python libraries:**

![n1](https://user-images.githubusercontent.com/95492893/144719369-b54a5945-598e-4116-9ec1-b63c662dbf84.PNG)

**Now we need to set up the path for training dataset as the dataset includes images only:**

![n2](https://user-images.githubusercontent.com/95492893/144719402-60bb7945-793c-4b2f-86fd-847863d4d539.PNG)

**Now let’s load the data for training or Machine Learning model for the task of Pneumonia Detection with Python:**

![n3](https://user-images.githubusercontent.com/95492893/144719432-8e363bfe-f25f-4644-b76f-9ff14f076782.PNG)

## Data Exploration

The dataset I’m using here is stored as .jpg files in 2 different folders, each folder with the model name of the images in the folder.

We need to use the ImageDataBunch.from_folder() function to load the images and assign tags to the images based on the name of the folder from which they are read:

![n4](https://user-images.githubusercontent.com/95492893/144719491-a97d3865-9ee9-4563-8621-76027b3c4176.PNG)

![image](https://user-images.githubusercontent.com/95492893/144719589-e4a7ba4b-b77b-491a-8dd6-776333a4d0f0.png)


## Using Machine Learning for Pneumonia Detection with Python

Now, I will use a pre-trained model known as ResNet50, which is a type of Convolutional Neural network in Machine Learning. Now let’s see how to use this model:

![n5](https://user-images.githubusercontent.com/95492893/144719516-b676f78b-8b2e-4e1d-8662-1f44124b3ecd.PNG)

**Now let’s have a look at the learning rate of the model:**
![n6](https://user-images.githubusercontent.com/95492893/144719553-f8107c65-419f-4328-9b9f-913841180aca.PNG)

![image](https://user-images.githubusercontent.com/95492893/144719612-6f4c1539-ddd0-4602-a8fb-d2abc9809445.png)


## Training and Testing the Model
**In the above section, we loaded the model. Now I will train the model on our dataset:**

![n7](https://user-images.githubusercontent.com/95492893/144719694-15051531-e140-474d-8396-38a4be456278.PNG)

**Now let’s test the model:**
![n8](https://user-images.githubusercontent.com/95492893/144719730-81116314-805d-41a8-9843-cebbdf2d4cbc.PNG)

![n9](https://user-images.githubusercontent.com/95492893/144719768-89d3f240-4cab-4e45-aeca-c60bbb7d5515.PNG)








