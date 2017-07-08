# Image-Captioning using InceptionV3 and Beam Search

Using Flickr8k dataset since the size is 1GB. MS-COCO is 14GB!

Used Keras with Tensorflow backend for the code. **InceptionV3** is used for extracting the features.

I am using Beam search with **k=3, 5, 7** and a normal max search for predicting the captions of the images.

The loss value of **2.8876** has been achieved which gives reasonable results. You can check out some examples below. The rest of the examples are in the jupyter notebook. You can run the Jupyter Notebook and try out your own examples.

Everything is implemented in the Jupyter notebook which will hopefully make it easier to understand the code.

# Examples

<img align="left" src="https://raw.githubusercontent.com/yashk2810/Image-Captioning/master/images/basketball.png">
<br />
<br />
**Normal Max search:** A man in a white uniform is and holding a ball in his hand while a man in a blue shirt is playing together to back around .
<br />
**Beam Search, k=3:** A man in a white shirt and white shorts is playing with a soccer ball .
<br />
**Beam Search, k=5:** A group of men in white uniforms playing basketball .
<br />
**Beam Search, k=7:** A group of men in white uniforms playing basketball .
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

<img align="left" src="https://raw.githubusercontent.com/yashk2810/Image-Captioning/master/images/snow_mountain.png">
**Normal Max search:** A man and a woman in a white jacket and white pants on a snowboard overlooking a white mountain .
<br />
**Beam Search, k=3:** A person in a white jacket and blue pants skiing through the snow .
<br />
**Beam Search, k=5:** A person in white pants and blue pants is in the snow .
<br />
**Beam Search, k=7:** A man on a mountain bike does a flip in the snow .
<br />

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
