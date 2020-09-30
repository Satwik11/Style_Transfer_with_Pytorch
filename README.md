# Style_Transfer_with_Pytorch

## Neural Style Transfer

Neural Style Transfer allows us to combine the style of an image with the content of a natural image by manipulating the feature representations learned by a Convolutional Neural Network. For example, it can enable us to transfer the style from Vincent van Gogh's The Starry Night to an image of Neckarfront in Tübingen.

![Test Image 1](https://github.com/zhanghang1989/PyTorch-Multi-Style-Transfer/raw/master/images/1.jpg)
![Test Image 2](https://github.com/zhanghang1989/PyTorch-Multi-Style-Transfer/raw/master/images/2.jpg)
![Test Image 3](https://github.com/zhanghang1989/PyTorch-Multi-Style-Transfer/raw/master/images/3.jpg)

## Implementation

All the images were generated using the Adam optimizer rather than the L-BFGS optimizer used in the original paper due to lack of resources. The content losses were calculated using the conv4_2 layer of the vgg19 network and the style losses were calculated using the conv1_1, conv2_1, conv3_1, conv4_1 and conv5_1 layers.

## Data Files
1. Pre-trained VGG19 network weights - put it in models/ directory
2. torchvision - torchvision.models contains the VGG19 model skeleton

## Dependecies
PyTorch
NumPy
Jupyter
opencv

## How to run the file
Execute Style_Tranfer.ipynb file an output video will be generated in which you can see photo conversion






