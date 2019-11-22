# EIP4
Assignment2 :

The strategy followed based on the given 8 DNN codes:
1) No use of bias. Thus,added use_bias=False
2) The last convolution layer is sacrosanct. Thus removed Batchnormation() and Dropout() from it.
3) After training this network with batch_size=32 and epochs=20, have observed each epoch run took 35s to 36s and for the 20th epoch, 
   the acc=0.9995 , val_acc=0.9903  , which clearly states the problem of overfitting(OF).
   
Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 36s 600us/step - loss: 0.0021 - acc: 0.9995 - val_loss: 0.0397 - val_acc: 0.9903
<keras.callbacks.History at 0x7f34b6a8c7f0>

Thus, introduced Dropout(0.1) after every convolution layer.
4) Dropout of 0.1 is added after every convolution layer.
5) Total params: 11,160
   Trainable params: 10,980
   Non-trainable params: 180
5) Score: [0.019890406434552095, 0.9943] This is achieved with batch_size=64,epochs=20

Log:
Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 35s 582us/step - loss: 0.0219 - acc: 0.9929 - val_loss: 0.0277 - val_acc: 0.9922
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 21s 356us/step - loss: 0.0184 - acc: 0.9938 - val_loss: 0.0213 - val_acc: 0.9928
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 21s 355us/step - loss: 0.0173 - acc: 0.9940 - val_loss: 0.0236 - val_acc: 0.9930
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 21s 358us/step - loss: 0.0149 - acc: 0.9950 - val_loss: 0.0199 - val_acc: 0.9938
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 21s 357us/step - loss: 0.0156 - acc: 0.9945 - val_loss: 0.0210 - val_acc: 0.9940
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 21s 356us/step - loss: 0.0144 - acc: 0.9950 - val_loss: 0.0213 - val_acc: 0.9931
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 22s 360us/step - loss: 0.0133 - acc: 0.9955 - val_loss: 0.0191 - val_acc: 0.9942
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 22s 360us/step - loss: 0.0133 - acc: 0.9955 - val_loss: 0.0200 - val_acc: 0.9939
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 21s 357us/step - loss: 0.0128 - acc: 0.9957 - val_loss: 0.0207 - val_acc: 0.9937
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 22s 365us/step - loss: 0.0129 - acc: 0.9956 - val_loss: 0.0210 - val_acc: 0.9934
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 22s 360us/step - loss: 0.0122 - acc: 0.9960 - val_loss: 0.0196 - val_acc: 0.9940
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 21s 358us/step - loss: 0.0123 - acc: 0.9959 - val_loss: 0.0223 - val_acc: 0.9935
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 21s 358us/step - loss: 0.0122 - acc: 0.9959 - val_loss: 0.0205 - val_acc: 0.9939
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 22s 361us/step - loss: 0.0122 - acc: 0.9960 - val_loss: 0.0198 - val_acc: 0.9938
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 22s 360us/step - loss: 0.0108 - acc: 0.9961 - val_loss: 0.0206 - val_acc: 0.9938
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 21s 357us/step - loss: 0.0113 - acc: 0.9957 - val_loss: 0.0207 - val_acc: 0.9941
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 21s 357us/step - loss: 0.0116 - acc: 0.9960 - val_loss: 0.0193 - val_acc: 0.9943
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 22s 359us/step - loss: 0.0109 - acc: 0.9963 - val_loss: 0.0198 - val_acc: 0.9941
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 21s 358us/step - loss: 0.0118 - acc: 0.9961 - val_loss: 0.0200 - val_acc: 0.9941
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 21s 357us/step - loss: 0.0108 - acc: 0.9965 - val_loss: 0.0199 - val_acc: 0.9943
<keras.callbacks.History at 0x7f34b53b60b8>


----------------------------------------------------------------------------------------------------------------------------------------




Assignment1 :
Print Score Result [0.17091783548227282, 0.9863]

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




