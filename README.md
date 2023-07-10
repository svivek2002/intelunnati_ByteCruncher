# intelunnati_ByteCruncher
This is the private repo of the project of my self built model for Conquering Fashion MNIST Dataset by CNN using Computer Vision under Intel® Unnati Industrial Training - Summer 2023.

The Fashion MNIST dataset consists of 70,000 grayscale pictures of apparel that are broken down into 10 categories, as indicated in Table 1: Sneaker, Trouser/Jeans, Handbag, Dress, Coat/Blazzer, Slipper/Sandal, Shirt, T-shirt/top, Pullover, and Ankle Boot. There are 784 features total for each image, which is a 28x28 pixel square. A model must be trained using the provided training set, which consists of 60,000 photos, and its performance must be assessed using the test set, which consists of 10,000 images. The test photographs should be able to be classified by the model into one of the 10 fashion categories.

This below shows the fashion mnist dataset with class labels
![image](https://github.com/svivek2002/intelunnati_ByteCruncher/assets/97838886/2bd90615-f6b7-4026-afe8-edb234824a51)

And this is my final CNN model architecture 
![image](https://github.com/svivek2002/intelunnati_ByteCruncher/assets/97838886/01deb1a7-b34f-4217-bd0f-a09e2ea06a3c)

This is classification report of my model
![image](https://github.com/svivek2002/intelunnati_ByteCruncher/assets/97838886/9dd45191-39b2-4538-8a6f-2d4640f43310)

My model gives 96% accuracy on training dataset and 90% on testing dataset without using regularization.

I thought the model is overfitting, so I used regularization , i.e. added some dense layers and dropout layers to the model and some extra covolutional and max. pooling layers. Also applied optimizers and got 92% accuracy on trainning and 90% on testing dataset.
