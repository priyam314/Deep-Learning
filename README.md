# Image Captioning
this is a deep learning project, which has used the concept of AutoEncoders or Popularly known as seq2seq models. 

## Description
the deep learning model takes input as an image and then tries to output a sentence which describes the image, like below
![](electric_bus.jpg)

will output 
`a red bus parked on a city street`

which is not exactly correct, but model was able to identify that object is bus, and its parked. Currently the model is in quite nascent stage, and with better datasets and architectures better results can be found.

## Architecture
 
In encoder, simple CNN layers are used. This will learn the complex representation of the image and objects, and store it in latent variable, or we say bottleneck layer.

In decoder, LSTM(Long Short Term Memory) is used, this will output next word on the basis of last word outputed. This is RNN architecture.

