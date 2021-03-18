# Image-captioning


Image captioning is a process of producing a textual description of a picture that used to generate captions and subtitles based on natural language processing and computer vision.

we can use an encoder that takes Images as input and extract their features, then theit=r features go to the next layer. in the end, the last layer connects to the decoder part.

for a specific picture, some noises make it difficult to describe the picture. Then we need an algorithm that extracts suitable features and deletes noises.
In this project, I used Arcitucture Inception V3 as an encoder.
In the decoding stage, at the first, the dataset tokenized and classified with tf.data API. next, I split the train and test and validation set. 

at the end of all, I tried to produce a Persian caption using google translate library in python
