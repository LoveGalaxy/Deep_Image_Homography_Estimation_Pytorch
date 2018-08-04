# Deep_Image_Homography_Estimation_Pytorch

## 1. Introduction
I read a interest paper named *Deep Image Homography Estimation*. You can download this paper at [here](https://arxiv.org/abs/1606.03798).

This paper present a method to estimation a homography matrix between two images. It only use a simple CNN to achieve.

And the paper didn't provide any code to recurrent. I am just learning PyTorch now.  So I try to implement this network by PyTorch.

## 2. About this repository

More detail about the network, please read the paper I provided above.

The dataset that author of paper used is MSCOCO 14. Now Microsoft provided MSCOCO 17 to download. You can download this data set at [here](http://cocodataset.org/#download). I used this dataset to train my network.

I divided this paper's work into two steps. First, use MSCOCO17 dataset to build train, validation and test dataset. Second, used the datasets to train, validate and test our network.

## 3. Requirement environment

- PyTorch 0.4.0
- opencv 3.*

## 4. Thank you for give me help and advice
If you see this description , I hope you can give me help and advice, any help and advice will be welcome.


