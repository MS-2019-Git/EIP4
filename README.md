# EIP4
Print Score Result [0.0028064302265603754, 0.9996]

1.Convolution- It is a method used to make the network learn and find out the edges,gradients,textures of the iput image. These are then combined to create the parts of objects and then an object.Convolution translates the input image through multiple layers.

2.Filters/Kernels - Channel is a container of a specific information.Kernel helps to extract this information.No. of kernels is equal to the no. of channels in the output. No. of channels in the input has no relation with the no. of channels in the output.

3.Epochs - Usually a dataset is comprised of multiple images. If the convolution completes one round of the dataset, it is called one epoch.

4.1X1 convolution - It is actually a single pixel.It helps in channel reduction by combining the features.It is used to reduce the number of channels and not to increase the no. of channels.

5.3X3 convolution - Using 3X3,we can have any kernel.The od number 3 is chosen to maintain the symmetry. Every single 3X3 is a superset of any 2X2.

6.Feature Maps-Thisis collection of all features.Kernel is not going to extract the feature but the feture itself should be present there so that it can be combined with other features.

7.Activation Function This is used in convolution method. Mostly commonly "relu" is used.

8.Receptive Field- Receptive field of the last layer must atleast be the size of the object and not the size of the full image.
The LRF local receptive field do not hold its neighbour's information.It is 3X3 in size.
The GRF Global receptive field  must see the whole object. It is 1X1 in size.




