# Fashion-MNIST

This repo holds the CNN code for classification of images which are labelled with 10 types of labels viz.
0 T-shirt/top
1 Trouser
2 Pullover
3 Dress
4 Coat
5 Sandal
6 Shirt
7 Sneaker
8 Bag
9 Ankle boot

If an image from these categories are fed to the model, then it will be able to label it correctly with an accuracy of 92.02%
In order to train the models Keras framework of python has been used with basic libraries such as numpy, matplotlib, pandas. 
The model is trained on 60,000 imaages. Each image is of 28x28 dimension and is labeled on 10 types of wearables.
The order it followed is :
Conv2D (ReLU) -> Max Pooling -> Dropout -> Flatten -> Fully Connected(ReLU) -> Softmax
In order to train the CNN the data has been preprocessed to obtained the flatten arrays of CSV in (28,28) form.
Rest of the information can be infered from the comments in the jupyter notebook.
