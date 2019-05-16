Bhagabat Prasad Behera
bhagabat.prasad123@gmail.com
Batch 6

# 1 x 1 Convolution

To control height and width of input, pooling can be used. However, to change the depth, 1 x 1 convolution can be used in computationally efficient way (unlike with "same" padding).  Because of its size, it does not operate on multiple elements of a feature map at a time, hence it does not capture any correlation among them. It is more focused on reducing the channel (in general cases) and help the network capture more complex function by adding non-linearity through activation function. 

![alt](https://i.ibb.co/swdsgNN/1x1-Andrew-Ng.png)

![alt](https://i.ibb.co/Fm1VnWL/1x1-How.png)





