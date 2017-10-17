# traffic-sign-recognition
Traffic Sign Classifier - Udacity Self-Driving Car Engineer Nanodegree.

### Environment setup ###

### How to use ###
1. Download training data. Open *raw_data* forlder for instructions.
2. Run *datasetProcessor.ipynb* in order to create augmented dataset for neural network training.
3. There is an option to download already processed dataset and skip steps 1 and 2. Please open *train_data* folder for instructions.
1. There is an additional evaluation stage based on images from the Internet. Make sure that the folder *test_data* is populated with *pickle* files. 
1. Execute *signClassifier.ipynb* and load data, train neural network, and evaluate its accuracy.
1. Additional analisys of neural network internals may be performed via *tensorboard*. Please, open *support* folder for instructions.

Folder *report* contains a report describing convolutional neural network architecture used in this project.

The accuracy:
* validation dataset - 0.96
* test dataset - 0.94
* images from internet - 0.6

Tipical Accuracy:
![](https://github.com/antonpavlov/traffic-sign-recognition/blob/master/support/readme_images/accuracy.png)

Cross entropy:
![](https://github.com/antonpavlov/traffic-sign-recognition/blob/master/support/readme_images/xent.png)

### License ###
All Jupyter notebooks and tensorboard data are distribuited with MIT license. Tensorflow is a framework developed by Google and opensource community. Please, refer to tensorflow.org web site of license terms.

### References ###
This work is hevaly based on the floowing article:

Pierre Sermanet and Yann LeCun: "Traffic Sign Recognition with Multi-Scale Convolutional Networks," Proceedings of International Joint Conference on Neural Networks (IJCNN'11), 2011. http://yann.lecun.com/exdb/publis/index.html