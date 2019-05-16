Bhagabat Prasad Behera
bhagabat.prasad123@gmail.com
Batch 6

# Epochs

An epoch is one time passing all the rows of a dataset to the network. We can pass the rows individually, or in batches or all at once. With each pass, the network minimizes error and improves the internal parameters. With large number of epochs the model gets more opportunity to minimize error sufficiently. However it can lead to overfitting and should be stopped on an epoch from where the validation score starts degrading.

![alt](https://i.ibb.co/ySh0mVp/Epochs.png)