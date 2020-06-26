# Bangkit, Final Project
This is our team's repository for completing on the final project about machine learning of Bangkit Course.

Our member are:
1. Ida Bagus Agung Nara Surya Darma
2. R. Arif Firdaus Lazuardi
3. Kadek Suar Wibawa
4. Putu Althea

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

##Knowledge

Convolutional Neural Networks
Artificial Neural Networks (ANN) is a computational processing system that is inspired by the way the biological nervous system (like the human brain) operates (O'Shea & Nash, 2015). One of the most impressive forms of ANN architecture is a Convolutional Neural Network (CNN).
Convolutional neural networks (CNN, Content) are a class of deep artificial neural networks, which can be applied to analyze visual images (Standford University, 2018). CNN consists of neurons that have weight, bias and function Activation. Like other neural networks, CNN consists of an input layer, a hidden layer and an output layer. These layers perform operations that convert data with the intention of learning the special features for the data. Three of the most common layers are: convolution, activation or ReLU, and unification (Matlab, n.d.).
 
![cnn](https://user-images.githubusercontent.com/61100033/85878393-3285c500-b80b-11ea-94de-d468b495b133.JPG)
CNN Architecture (Source: Matlab)

Transfer Learning VGG16
Transfer learning is the process of transferring knowledge from other pre-trained network models to the model created. Transfer learning is useful to speed up the training process while increasing training performance by using weights in the original architectural training process as a whole. TThere are several pre-trained networks, one of which is VGG16. VGG16 is one of the VGGnet models that uses 16 layers as an architectural model. VGG16 consists of 5 convolutional blocks before connecting to the multilayer perceptron (MLP) classifier. Convolutional blocks are connected to three MLP layers consisting of two hidden layers and one output layer. The output layer consists of nodes that directly represent the number of classes and with softmax activation functions (for number of classes more than two) or sigmoid activation functions (for number of classes less than or equal to two) (Haqmi Abas, Ismail, Mohd Yassin, & Taib , 2018).

![vgg](https://user-images.githubusercontent.com/61100033/85878524-6b259e80-b80b-11ea-9cf9-9c7ea3e134fe.JPG)
(Source: https://towardsdatascience.com/step-by-step-vgg16-implementation-in-keras-forbeginners-a833c686ae6c)
Overfitting
Overfitting is common in machine learning, in this case the model does not generalize the observed data. Overfitting causes the possibility of the model being trained perfectly in the training dataset, but not quite fitting in the testing dataset. generaly, overfitting can occur when training data is very small in number or has data that is not representative or too much noise. This situation makes noise most likely to be trained and then acts as a prediction basis. overfitting can also occur when there are complex hypotheses. The concept of statistics and machine learning is a compromise between variance and bias.

Reference
O'Shea, K. T., & Nash, R. (2015). An Introduction to Convolutional Neural
Networks. ArXiv e-prints.
Standford University. (2018, February 23). Introduction to Convolutional Neural
Networks. Retrieved from Stanford University:
https://web.stanford.edu/class/cs231a/lectures/intro_cnn.pdf
Matlab. (n.d.). Convolutional Neural Network. Retrieved April 25, 2019, from Mathworks 
https://www.mathworks.com/solutions/deep learning/convolutional-neural-network.html\

Haqmi Abas, M. A., Ismail, N., Mohd Yassin, A. I., & Taib, M. N. (2018). VGG16
for Plant Image Classification with Transfer Learning and Data Augmentation. International Journal of Engineering & Technolog, 90-94.

Hridayami, P., Darma Putra, I., & Wibawa, K. S. (2019). Fish Species Recognition
Using VGG16 Deep Convolutional. Journal of Computing Science and
Engineering, 13(3), 124-130.

--oO Thanks Praba Oo--
