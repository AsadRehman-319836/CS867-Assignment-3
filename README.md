# CV-Assignment_3

This repository contains four google colab notebook files which is a part of Assignment 3. Keras open source python library is used in these projects. To get the pretrained weights obtained from these goto following links.
1. For model that is trained on constant learning rate without data augmetation click [here](https://drive.google.com/file/d/11NJzaEh_RGWqth-SsN51lG4GZuX3gBED/view?usp=sharing)
2. For model that is trained on constant learning rate with data augmetation click [here](https://drive.google.com/file/d/1Oa_st4H0gPGMbFA2Mz2TI-5WANxWAis3/view?usp=sharing)
3. For model that is trained on time based decaing learning rate with data augmetation click [here](https://drive.google.com/file/d/1WdBdZVzA2kPQ8yQ45G6J5PDVHiHyA04O/view?usp=sharing)
4. For model that is trained on Adam Optimizer with data augmetation click [here](https://drive.google.com/file/d/1jUZnXDfAe9gvbbnujXbLNnPg35EjCMqL/view?usp=sharing)

To use above weights, import VGG16 model in jupiter notebook and load those model using keras.model.load_weights(file.h5). 

In colab notebook avaiable in this repository VGG16 network is trained with some parameters which are different from each other. 
1. [VGG16 model is trained without dataset augmentation and with constant learning rate](https://github.com/AsadRehman-319836/CS867-Assignment-3/blob/main/No%20Augmentation%20VGG16_with_Constant_lr.ipynb)
2. [VGG16 model is trained with dataset augmentation and with constant learning rate](https://github.com/AsadRehman-319836/CS867-Assignment-3/blob/main/VGG16_with_Constant_lr.ipynb)
3. [VGG16 model is trained with dataset augmentation and with decaying learning rate](https://github.com/AsadRehman-319836/CS867-Assignment-3/blob/main/VGG16_with_Time-Based_Decay.ipynb)
4. [VGG16 model is trained with dataset augmentation and with Adam Optimizer](https://github.com/AsadRehman-319836/CS867-Assignment-3/blob/main/VGG16_with_Adam_opt.ipynb)


![alt text](https://github.com/AsadRehman-319836/CS867-Assignment-3/blob/main/VGG16.png)
