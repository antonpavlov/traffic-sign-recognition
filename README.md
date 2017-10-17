# traffic-sign-recognition
Traffic Sign Classifier - Udacity Self-Driving Car Engineer Nanodegree.

The purpose of this project is to classify images of German traffic signs using convolutional neural network.


### Environment setup ###
Tensorflow 0.12 and above for neural network training and evaluation. Detailed instructions are [here](https://github.com/udacity/CarND-Term1-Starter-Kit.git).

[Tensorflow](https://www.tensorflow.org/install/) 1.3 and above for dataset preprocessing and training data augmentation. 


### How to use ###
* Download training data. Open *raw_data* folder for instructions.
* Run *datasetProcessor.ipynb* in order to create augmented dataset for neural network training.
* There is an option to download already processed dataset and skip steps 1 and 2. Please open *train_data* folder for instructions.
* There is an additional evaluation stage based on images from the Internet. Make sure that the folder *test_data* is populated with *pickle* files. 
* Execute *signClassifier.ipynb* and load data, train neural network, and evaluate its accuracy.
* Additional analisys of neural network internals may be performed via *tensorboard*. Please, open *support* folder for instructions.

Folder *report* contains a report describing convolutional neural network architecture used in this project.

The accuracy:
* validation dataset - 0.96
* test dataset - 0.94
* images from internet - 0.6

Tipical Accuracy:<br/>


![](https://github.com/antonpavlov/traffic-sign-recognition/blob/master/support/readme_images/accuracy.png)

Cross entropy:<br/>


![](https://github.com/antonpavlov/traffic-sign-recognition/blob/master/support/readme_images/xent.png)

### License ###
All Jupyter notebooks and tensorboard data are distribuited with MIT license. Tensorflow is a framework developed by Google and open-source community. Please, refer to tensorflow.org web site for license terms.

### References ###
This work is hevaly based on the floowing article:
Pierre Sermanet and Yann LeCun: **"Traffic Sign Recognition with Multi-Scale Convolutional Networks,"** Proceedings of International Joint Conference on Neural Networks (IJCNN'11), 2011. http://yann.lecun.com/exdb/publis/index.html