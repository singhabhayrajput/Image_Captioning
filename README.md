# What is Image Captioning?
Image Captioning refers to the process of generating a textual description from a given image based on the objects and actions in the image.

Image captioning was one of the most challenging tasks in the domain of Artificial Intelligence (A.I).


# Working of Image Captioning


The core idea behind image captioning is to combine and utilize the concepts of Computer Vision and Natural Language Processing. This task of image captioning is composed of two logical models which are namely an Image-based model and a Language-based model. The former is responsible for extracting the features out of a given image while the latter translates the features and objects provided by the image-based model to a natural sentence.

The Convolutional Neural Network (CNN) does the image processing and feature extraction related work while on the other hand Recurrent Neural Network (RNN) subsequently generates the required textual description (captions) using the features learned by CNN. This overall model/architecture is commonly termed as Encoder-Decoder model.

Here, Encoder is the Image-based model (CNN) while the Decoder is the Language-based model (RNN).
