# Convolutional neural network


About the files:

cnn.py: This is the main file that you will execute. It will read and processing CIFAR10 dataset, and run models.

- There are 2 models:
  o Simple Model, an example of a convolutional neural network which already implemented.
  o Complex Model, you have to implement model follow the architecture below.
      - 7x7 Conv with stride 2
      - Relu activation
      - 2x2 Max Pooling
      - Fully connected with 1024 hidden neurons
      - Relu activation
      - Fully connected that map to 10 output classes
       
 Setup and installation
- You need to create CPU instance on google cloud for this (Ubuntu 16.04), since nGraph only support Xeon processor or you can run it on Google Colab.
- Run “sudo pip3 install -U tensorflow” to install tensorflow
- Run “sudo pip3 isntall -U ngraph-tensorflow-bridge” to install nGgraph.
