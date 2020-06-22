## Diabetic Retinopathy Image Recognition Project
This is our team's repository for completing on the final project about machine learning from Google Bangkit Academy

Our team member are:
1. Bagus
2. R. Arif Firdaus Lazuardi
3. Kadek Suar Wibawa
4. Putu Althea Putri Wiradani

## Prerequisites
1. Jupyter Notebook or Google Colab
2. Python version 3.6 or above
3. Latest version of Tensorflow 2
4. Diabetic Retinopathy dataset

## Directory Structure 
- dataset
- doc
- apps
  - web
  - model

Explanation:
- dataset = dataset that has been downloaded. Local use purpose.
- doc = snaps note and for put all docs about our code
- apps = our apps (both model and client side software)
- apps/web = all of source code for web application
- apps/model = all of jupyter notebook files (save as google colab as notebook) / python files

## About This Project
In this project we build a image classification recognition model that would recognize the digital color fundus photograph from the retinal part of the patient’s eyes, based on the public dataset diabetic retinopathy resized_train_15_19_DG which available on Kaggle. The dataset contain 5 classes which are 0 for No DR, 1 for Mild, 2 for Moderate, 3 for Severe, and 4 for Proliferative DR with total 15 GB sizes and separated into 92.9K image pictures and 5 csv tables.

![DR](https://user-images.githubusercontent.com/61100019/85304991-9d1ac600-b4d6-11ea-90f8-a5e6c1a00816.JPG)

While develop our model, we used pre-trained VGG without using the top layer from the VGG itself. Instead of using the top layer of VGG, we added AveragePooling2D, two hidden layer, and output layer containing 5 neurons because there are 5 class in this dataset.

As a result from using VGG-19 model, we have got higher validation accuracy. We developed a model that produces 70% training accuracy and 70% validation accuracy.
