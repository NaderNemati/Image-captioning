# Image-captioning

Image captioning is a process of producing textual description of a picture that used to generate captions and subtitles bassed on natural languague proccessing and computer vision.

we can use a an encoder that takes Images as input and extract their features, then theit=r features go to nest layer.at the end, the last layer connect to decoder part.

for a specific pictuer some noises that make difficult descibing picture. Ten we need an algorithm that extract suitable features and delete noises.
In this project I used Arcitucture Inception V# as a encoder.
In decoding stage,at the first, dataset tokenized and classified with tf.data API.next I splitted train and test and validation set. 

at the end of all, I tried to produse a persian caption using google translate library in python
