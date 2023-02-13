# Neural_network - classify_images
Zalando is a multinational e-commerce platform selling fashion goods in many European countries. It released a Fashion MNIST dataset – a set of (60,000 train + 10,000 test, stored in fashion-mnist_train.zip and fashion-mnist_test.zip) images of 10 types of clothes.

![image](https://user-images.githubusercontent.com/53173112/218428531-4d81710c-b643-4350-bc37-625637e9cff0.png)

In this code I create neural network with few hidden layers to classify images in Fashion MNIST dataset. Then I “Play” with the number of the hidden layers and size of each layer. For each case, I measure:

i. The total number of network parameters
ii. The network accuracy on the training and validation set (for each batch).
iii. Training and inference times.


What can we learn from these experiments? Can they help as choose the best model?
I use some plots to make my arguments easier to convey. 

Then I test performance of the model in the test set, and add confusion matrix. 
