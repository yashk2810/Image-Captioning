# Image-Captioning using InceptionV3 and Beam Search

Using Flickr8k dataset since the size is 1GB. MS-COCO is 14GB!

Used Keras with Tensorflow backend for the code. *InceptionV3* is used for extracting the features.

I am using Beam search with *k=3, 5, 7* and a normal max search for predicting the captions of the images.

The loss value of *2.8876* has been achieved which gives reasonable results. You can check out some examples below. The rest of the examples are in the jupyter notebook. You can run the Jupyter Notebook and try out your own examples.

Everything is implemented in the Jupyter notebook which will hopefully make it easier to understand the code.

You can download the weights <a href='https://github.com/yashk2810/Image-Captioning/raw/master/weights/time_inceptionV3_2.8876_loss.h5'>here</a>.

# Examples



# Dependencies

* Keras 1.2.2
* Tensorflow 0.12.1
* tqdm
* numpy
* pandas
* matplotlib
* pickle
* PIL
* glob
