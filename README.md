# intelunnati_ByteCruncher
This model is for Conquering/ classifying Fashion MNIST Dataset by CNN using Computer Vision under Intel® Unnati Industrial Training - Summer 2023.

The Fashion MNIST dataset consists of 70,000 grayscale pictures of apparel that are broken down into 10 categories, as indicated in Table 1: Sneaker, Trouser/Jeans, Handbag, Dress, Coat/Blazzer, Slipper/Sandal, Shirt, T-shirt/top, Pullover, and Ankle Boot. There are 784 features total for each image, which is a 28x28 pixel square. A model must be trained using the provided training set, which consists of 60,000 photos, and its performance must be assessed using the test set, which consists of 10,000 images. The test photographs should be able to be classified by the model into one of the 10 fashion categories.

This below shows the fashion mnist dataset with class labels
![image](https://github.com/svivek2002/intelunnati_ByteCruncher/assets/97838886/e560f04b-a31b-4278-8637-701bfb6a82b1)


And this is my final CNN model architecture 
![image](https://github.com/svivek2002/intelunnati_ByteCruncher/assets/97838886/c5f95270-13d5-467d-9b10-070dd22be933)


This is classification report of my model

![image](https://github.com/svivek2002/intelunnati_ByteCruncher/assets/97838886/749d62ee-d16f-403d-88f8-db3dd78ce69f)


My model gives 96% accuracy on training dataset and 90% on testing dataset without using regularization.

I thought the model is overfitting, so I used regularization , i.e. added some dense layers and dropout layers to the model and some extra covolutional and max. pooling layers. Also applied optimizers and got 92% accuracy on trainning and 90% on testing dataset.
