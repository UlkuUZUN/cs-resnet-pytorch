# Cycle-Spinning (CS) method is applied to Antialiased CNNs 
**Making Convolutional Networks Shift-Invariant Again** <br>
[Richard Zhang](https://richzhang.github.io/). In [ICML, 2019](https://arxiv.org/abs/1904.11486)
[[Project Page]](http://richzhang.github.io/antialiased-cnns/) .

antialiased_cnns/resnet.py file has been changed with adding cycle-spinning method for ResNet. 

We did not change any parameter only add cycle-spinning method into resnet file and we named as resnet_padding_shif. If tis file named as resnet.py and run it is trained with cycle-spinning method. We have used ZeroPad2d for shift the images for first conv operation and after convolved undo shift operation.
