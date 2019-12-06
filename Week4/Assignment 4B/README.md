Assignment 4 RESNET WITH CUTOUT AND GRADCAM
-------------------------------------------

Have tried 8 models of Resnet with v1 and V2 , data augmentation, different learning rates,CutOuts. Observed the val_acc for each network. Then presented the final code with 88.51% acuuracy with cutout and gradcam.


Code1_ Resnet20V1 
------------------
with params=274,442 with real-time data augmentation lr=0.001 batch_size=32 epochs=30 
  Test loss: 0.7670399613380432
  Test accuracy: 0.8144


Code2_ Resnet20V1 _withCutOut
------------------------------
with params=274,442 with real-time data augmentation and CutOut(pixel_level=False) lr=0.001 batch_size=32 epochs=30
Test loss: 0.7128704925537109
Test accuracy: 0.8263


Code3_ Resnet20V1 _withCutOut
------------------------------
with params=274,442 with real-time data augmentation and CutOut(pixel_level=True) lr=0.001 batch_size=32 epochs=30
Test loss: 0.8042539792060852
Test accuracy: 0.8046


Code4_ Resnet20V2 _withCutOut
------------------------------
with params=849,002 with real-time data augmentation and CutOut(pixel_level=False) lr=0.001 batch_size=32 epochs=30
Test loss: 0.8395467792510987
Test accuracy: 0.8042

Code5_ Resnet20V1_withCutOut
-------------------------------  
with params=274,442 with real-time data augmentation and CutOut(pixel_level=False) lr=0.001 batch_size=128 epochs=50
Test loss: 0.6190543553352356
Test accuracy: 0.8471


Code6_ Resnet20V1_withCutOut 
---------------------------- 
with params=274,442 with real-time data augmentation and CutOut(pixel_level=False) batch_size=128 epochs=50

used lr_scheduler and reducer 
lr = 0.001
    if epoch > 40:
        lr *= 0.005
    elif epoch > 30:
        lr *= 0.001
    elif epoch > 20:
        lr *= 0.001
    elif epoch > 10:
        lr *= 0.1

Observation: After 20th epoch, the network is not learning much.
Test loss: 0.6093135005474091
Test accuracy: 0.843

Code7_ Resnet20V1_withCutOut_modifiedlr
---------------------------------------
with params=274,442 with real-time data augmentation and CutOut(pixel_level=False) batch_size=128 epochs=50
modified lr:
  lr = 0.01 
      if epoch > 30:
          lr *= 0.1   
      if epoch > 20:
          lr *= 0.1
      elif epoch > 10:
          lr *= 0.1
Test loss: 0.5430240948200226
Test accuracy: 0.8542


Code8_ Resnet20V1_withCutOut_withmodifiedlr
---------------------------------------
with params=274,442 with real-time data augmentation and CutOut(pixel_level=False) batch_size=128 epochs=50
modified lr:
   lr = 0.001 
      if epoch > 50:
          lr *= 0.1   
      if epoch > 40:
          lr *= 0.1
      elif epoch > 30:
          lr *= 0.1

Test loss: 0.484324564409256
Test accuracy: 0.8851  
               
               
FinalCode_ Resnet20V1_CutOut_GradCam
-------------------------------------------
with params=274,442 with real-time data augmentation and CutOut(pixel_level=False) batch_size=128 epochs=50
modified lr:
   lr = 0.001 
      if epoch > 50:
          lr *= 0.1   
      if epoch > 40:
          lr *= 0.1
      elif epoch > 30:
          lr *= 0.1

Test loss: 0.484324564409256
Test accuracy: 0.8851  
               ------


   

