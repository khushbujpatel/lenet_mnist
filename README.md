# lenet_mnist
PyTorch based Neural Network for MNIST Dataset Classification (LeNet)

# Requirements

To install required packages, run following command

```
~$ sudo -H python3 -m pip install -r requirements.txt
```

# Train

To train model with MNIST Dataset, run following command.

```
~$ python3 train.py --batch-size 32 --test-batch-size 32 --epochs 5 --no-cuda --save-model
```

Trained model ```mnist_cnn.pt``` log can be found in ```train.log``` and is trained to Test Accuracy of 99% on MNIST dataset.


