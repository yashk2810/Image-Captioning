# Image-Captioning using InceptionV3 and Beam Search

Using Flickr8k dataset since the size is 1GB. MS-COCO is 14GB!

Used Keras with Tensorflow backend for the code. InceptionV3 is used for extracting the features.

# Examples

<img align="left" src="https://raw.githubusercontent.com/yashk2810/Image-Captioning/master/images/basketball.png">

**Normal Max search:** A man in a white uniform is and holding a ball in his hand while a man in a blue shirt is playing together to back around .
<br />
**Beam Search, k=3:** A man in a white shirt and white shorts is playing with a soccer ball .
<br />
**Beam Search, k=5:** A group of men in white uniforms playing basketball .
<br />
**Beam Search, k=7:** A group of men in white uniforms playing basketball .
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
