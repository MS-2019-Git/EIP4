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
