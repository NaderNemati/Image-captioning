# Image-captioning

Image Captioning is the process of generating textual description of an image. It uses both Natural Language Processing and Computer Vision to generate the captions.
The dataset consists of input images and their corresponding output captions.I used a neural network as a encoder to extract features that at the last layer connected to other part named 
decoder.In this project I used Inception V3 model designed by Google as the encoder part.I splite data set to train test and validation set by tf.data API.
