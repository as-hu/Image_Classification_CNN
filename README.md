# Image Classification CNN

Image classifier build using Tensorflow.
Image classification is the process of taking an input (like a picture) and outputting a class (like “cat”) or a probability that the input is a particular class (“there’s a 90% probability that this input is a cat”).
Convolution Neural Network is good for Image Classification because in this type of Neural network a Neuron of a particular layer is Connected to the small portion of the layer before it.
Another reason as to why we can not use Fully Conneted network is that it will require large number of Neurons and ultimately it will lead to overfitting.

Here,the coloured image is read as three channels->
1.Red 2.Green 3.Blue
These channels are stacked up to form a 3-D matrix where cell represents a pixel value.

CNN compares the Images piece by piece these pieces are called features.Now, we take these featues and match it with the entire images.
If it is Matched then that particular image is correct.


The Entire Process consist of some steps->
1. The Image is converted into a 3D matrix.
2. Then we will pass the matrix through different layers.
3. Basically There are 4 layers- convolution Layer, Relu layer ,pooling layer,fully connected layer.

These 4 layers performs different functions to classify the image.
