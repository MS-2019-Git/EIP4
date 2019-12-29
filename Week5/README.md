Executed the code with different model and weights. Implemented cut out and data augmentation.
Final Code Result:
---------------------
{'age_output_acc': 0.35080645161290325, 'age_output_loss': 5.5875885563512, 'bag_output_acc': 0.6038306451612904, 'bag_output_loss': 3.610886966028521, 'emotion_output_acc': 0.6244959677419355, 'emotion_output_loss': 3.4993795118024273, 'footwear_output_acc': 0.6219758064516129, 'footwear_output_loss': 3.2563409651479414, 'gender_output_acc': 0.7782258064516129, 'gender_output_loss': 1.9108689062057003, 'image_quality_output_acc': 0.4737903225806452, 'image_quality_output_loss': 3.8108198412003054, 'loss': 27.689685267786825, 'pose_output_acc': 0.7469758064516129, 'pose_output_loss': 2.3652066415356052, 'weight_output_acc': 0.5695564516129032, 'weight_output_loss': 3.648593471896264}

LOG:
----------------------

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
360/360 [==============================] - 110s 306ms/step - loss: 7.9465 - gender_output_loss: 0.6877 - image_quality_output_loss: 0.9920 - age_output_loss: 1.4388 - weight_output_loss: 1.0019 - bag_output_loss: 0.9235 - footwear_output_loss: 1.0463 - pose_output_loss: 0.9359 - emotion_output_loss: 0.9205 - gender_output_acc: 0.5600 - image_quality_output_acc: 0.5510 - age_output_acc: 0.3985 - weight_output_acc: 0.6306 - bag_output_acc: 0.5661 - footwear_output_acc: 0.4446 - pose_output_acc: 0.6167 - emotion_output_acc: 0.7142 - val_loss: 7.9840 - val_gender_output_loss: 0.6849 - val_image_quality_output_loss: 0.9841 - val_age_output_loss: 1.4495 - val_weight_output_loss: 0.9849 - val_bag_output_loss: 0.9401 - val_footwear_output_loss: 1.0445 - val_pose_output_loss: 0.9278 - val_emotion_output_loss: 0.9682 - val_gender_output_acc: 0.5635 - val_image_quality_output_acc: 0.5559 - val_age_output_acc: 0.3659 - val_weight_output_acc: 0.6401 - val_bag_output_acc: 0.5479 - val_footwear_output_acc: 0.4425 - val_pose_output_acc: 0.6149 - val_emotion_output_acc: 0.6845

Epoch 00001: val_loss improved from inf to 7.98395, saving model to /content/saved_models/VGG19_model.001.h5
Epoch 2/50

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
360/360 [==============================] - 92s 255ms/step - loss: 7.8300 - gender_output_loss: 0.6834 - image_quality_output_loss: 0.9811 - age_output_loss: 1.4248 - weight_output_loss: 0.9843 - bag_output_loss: 0.9136 - footwear_output_loss: 1.0172 - pose_output_loss: 0.9274 - emotion_output_loss: 0.8981 - gender_output_acc: 0.5624 - image_quality_output_acc: 0.5532 - age_output_acc: 0.4033 - weight_output_acc: 0.6345 - bag_output_acc: 0.5667 - footwear_output_acc: 0.4875 - pose_output_acc: 0.6181 - emotion_output_acc: 0.7161 - val_loss: 7.8716 - val_gender_output_loss: 0.6726 - val_image_quality_output_loss: 0.9814 - val_age_output_loss: 1.4459 - val_weight_output_loss: 0.9786 - val_bag_output_loss: 0.9309 - val_footwear_output_loss: 0.9765 - val_pose_output_loss: 0.9255 - val_emotion_output_loss: 0.9602 - val_gender_output_acc: 0.5640 - val_image_quality_output_acc: 0.5559 - val_age_output_acc: 0.3659 - val_weight_output_acc: 0.6401 - val_bag_output_acc: 0.5479 - val_footwear_output_acc: 0.5494 - val_pose_output_acc: 0.6149 - val_emotion_output_acc: 0.6845

Epoch 00002: val_loss improved from 7.98395 to 7.87164, saving model to /content/saved_models/VGG19_model.002.h5
Epoch 3/50

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
360/360 [==============================] - 92s 255ms/step - loss: 7.7058 - gender_output_loss: 0.6648 - image_quality_output_loss: 0.9811 - age_output_loss: 1.4128 - weight_output_loss: 0.9822 - bag_output_loss: 0.9064 - footwear_output_loss: 0.9337 - pose_output_loss: 0.9248 - emotion_output_loss: 0.8999 - gender_output_acc: 0.5807 - image_quality_output_acc: 0.5526 - age_output_acc: 0.4005 - weight_output_acc: 0.6344 - bag_output_acc: 0.5670 - footwear_output_acc: 0.5753 - pose_output_acc: 0.6184 - emotion_output_acc: 0.7159 - val_loss: 7.8097 - val_gender_output_loss: 0.6446 - val_image_quality_output_loss: 0.9867 - val_age_output_loss: 1.4391 - val_weight_output_loss: 0.9821 - val_bag_output_loss: 0.9378 - val_footwear_output_loss: 0.9170 - val_pose_output_loss: 0.9160 - val_emotion_output_loss: 0.9864 - val_gender_output_acc: 0.6038 - val_image_quality_output_acc: 0.5549 - val_age_output_acc: 0.3659 - val_weight_output_acc: 0.6401 - val_bag_output_acc: 0.5358 - val_footwear_output_acc: 0.5822 - val_pose_output_acc: 0.6149 - val_emotion_output_acc: 0.6845

Epoch 00003: val_loss improved from 7.87164 to 7.80966, saving model to /content/saved_models/VGG19_model.003.h5
Epoch 4/50

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
360/360 [==============================] - 92s 255ms/step - loss: 7.5950 - gender_output_loss: 0.6452 - image_quality_output_loss: 0.9792 - age_output_loss: 1.4005 - weight_output_loss: 0.9746 - bag_output_loss: 0.8993 - footwear_output_loss: 0.8874 - pose_output_loss: 0.9130 - emotion_output_loss: 0.8959 - gender_output_acc: 0.6144 - image_quality_output_acc: 0.5520 - age_output_acc: 0.4020 - weight_output_acc: 0.6344 - bag_output_acc: 0.5694 - footwear_output_acc: 0.5975 - pose_output_acc: 0.6181 - emotion_output_acc: 0.7161 - val_loss: 7.6692 - val_gender_output_loss: 0.6253 - val_image_quality_output_loss: 0.9772 - val_age_output_loss: 1.4231 - val_weight_output_loss: 0.9748 - val_bag_output_loss: 0.9253 - val_footwear_output_loss: 0.8856 - val_pose_output_loss: 0.9007 - val_emotion_output_loss: 0.9571 - val_gender_output_acc: 0.6421 - val_image_quality_output_acc: 0.5559 - val_age_output_acc: 0.3695 - val_weight_output_acc: 0.6401 - val_bag_output_acc: 0.5660 - val_footwear_output_acc: 0.5887 - val_pose_output_acc: 0.6149 - val_emotion_output_acc: 0.6845

Epoch 00004: val_loss improved from 7.80966 to 7.66919, saving model to /content/saved_models/VGG19_model.004.h5
Epoch 5/50

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
360/360 [==============================] - 92s 255ms/step - loss: 7.4912 - gender_output_loss: 0.6170 - image_quality_output_loss: 0.9746 - age_output_loss: 1.3952 - weight_output_loss: 0.9721 - bag_output_loss: 0.8938 - footwear_output_loss: 0.8622 - pose_output_loss: 0.8841 - emotion_output_loss: 0.8924 - gender_output_acc: 0.6549 - image_quality_output_acc: 0.5522 - age_output_acc: 0.3996 - weight_output_acc: 0.6349 - bag_output_acc: 0.5715 - footwear_output_acc: 0.6109 - pose_output_acc: 0.6227 - emotion_output_acc: 0.7161 - val_loss: 7.5816 - val_gender_output_loss: 0.6008 - val_image_quality_output_loss: 0.9777 - val_age_output_loss: 1.4261 - val_weight_output_loss: 0.9770 - val_bag_output_loss: 0.9083 - val_footwear_output_loss: 0.8583 - val_pose_output_loss: 0.8786 - val_emotion_output_loss: 0.9547 - val_gender_output_acc: 0.6598 - val_image_quality_output_acc: 0.5559 - val_age_output_acc: 0.3684 - val_weight_output_acc: 0.6401 - val_bag_output_acc: 0.5620 - val_footwear_output_acc: 0.6018 - val_pose_output_acc: 0.6240 - val_emotion_output_acc: 0.6845

Epoch 00005: val_loss improved from 7.66919 to 7.58156, saving model to /content/saved_models/VGG19_model.005.h5
Epoch 6/50

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
360/360 [==============================] - 92s 256ms/step - loss: 7.3699 - gender_output_loss: 0.5883 - image_quality_output_loss: 0.9737 - age_output_loss: 1.3922 - weight_output_loss: 0.9683 - bag_output_loss: 0.8817 - footwear_output_loss: 0.8379 - pose_output_loss: 0.8391 - emotion_output_loss: 0.8887 - gender_output_acc: 0.6878 - image_quality_output_acc: 0.5524 - age_output_acc: 0.4056 - weight_output_acc: 0.6342 - bag_output_acc: 0.5813 - footwear_output_acc: 0.6241 - pose_output_acc: 0.6339 - emotion_output_acc: 0.7161 - val_loss: 7.5065 - val_gender_output_loss: 0.5911 - val_image_quality_output_loss: 0.9712 - val_age_output_loss: 1.4228 - val_weight_output_loss: 0.9731 - val_bag_output_loss: 0.9025 - val_footwear_output_loss: 0.8766 - val_pose_output_loss: 0.8179 - val_emotion_output_loss: 0.9512 - val_gender_output_acc: 0.6769 - val_image_quality_output_acc: 0.5559 - val_age_output_acc: 0.3664 - val_weight_output_acc: 0.6401 - val_bag_output_acc: 0.5675 - val_footwear_output_acc: 0.5877 - val_pose_output_acc: 0.6426 - val_emotion_output_acc: 0.6845

Epoch 00006: val_loss improved from 7.58156 to 7.50646, saving model to /content/saved_models/VGG19_model.006.h5
Epoch 7/50

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
360/360 [==============================] - 92s 255ms/step - loss: 7.2472 - gender_output_loss: 0.5669 - image_quality_output_loss: 0.9701 - age_output_loss: 1.3874 - weight_output_loss: 0.9624 - bag_output_loss: 0.8741 - footwear_output_loss: 0.8220 - pose_output_loss: 0.7800 - emotion_output_loss: 0.8842 - gender_output_acc: 0.7026 - image_quality_output_acc: 0.5531 - age_output_acc: 0.4089 - weight_output_acc: 0.6345 - bag_output_acc: 0.5928 - footwear_output_acc: 0.6370 - pose_output_acc: 0.6650 - emotion_output_acc: 0.7161 - val_loss: 7.3133 - val_gender_output_loss: 0.5524 - val_image_quality_output_loss: 0.9677 - val_age_output_loss: 1.4170 - val_weight_output_loss: 0.9672 - val_bag_output_loss: 0.8879 - val_footwear_output_loss: 0.8364 - val_pose_output_loss: 0.7441 - val_emotion_output_loss: 0.9407 - val_gender_output_acc: 0.7162 - val_image_quality_output_acc: 0.5559 - val_age_output_acc: 0.3720 - val_weight_output_acc: 0.6416 - val_bag_output_acc: 0.5796 - val_footwear_output_acc: 0.6184 - val_pose_output_acc: 0.6764 - val_emotion_output_acc: 0.6845

Epoch 00007: val_loss improved from 7.50646 to 7.31330, saving model to /content/saved_models/VGG19_model.007.h5
Epoch 8/50

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
360/360 [==============================] - 92s 255ms/step - loss: 7.1105 - gender_output_loss: 0.5429 - image_quality_output_loss: 0.9662 - age_output_loss: 1.3807 - weight_output_loss: 0.9612 - bag_output_loss: 0.8661 - footwear_output_loss: 0.8064 - pose_output_loss: 0.7094 - emotion_output_loss: 0.8778 - gender_output_acc: 0.7214 - image_quality_output_acc: 0.5543 - age_output_acc: 0.4068 - weight_output_acc: 0.6353 - bag_output_acc: 0.5975 - footwear_output_acc: 0.6407 - pose_output_acc: 0.7000 - emotion_output_acc: 0.7162 - val_loss: 7.2196 - val_gender_output_loss: 0.5474 - val_image_quality_output_loss: 0.9651 - val_age_output_loss: 1.4095 - val_weight_output_loss: 0.9570 - val_bag_output_loss: 0.8819 - val_footwear_output_loss: 0.8381 - val_pose_output_loss: 0.6868 - val_emotion_output_loss: 0.9339 - val_gender_output_acc: 0.7162 - val_image_quality_output_acc: 0.5514 - val_age_output_acc: 0.3765 - val_weight_output_acc: 0.6416 - val_bag_output_acc: 0.5806 - val_footwear_output_acc: 0.6164 - val_pose_output_acc: 0.7056 - val_emotion_output_acc: 0.6845

Epoch 00008: val_loss improved from 7.31330 to 7.21956, saving model to /content/saved_models/VGG19_model.008.h5
Epoch 9/50

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
360/360 [==============================] - 92s 256ms/step - loss: 6.9917 - gender_output_loss: 0.5177 - image_quality_output_loss: 0.9639 - age_output_loss: 1.3745 - weight_output_loss: 0.9554 - bag_output_loss: 0.8540 - footwear_output_loss: 0.7928 - pose_output_loss: 0.6612 - emotion_output_loss: 0.8722 - gender_output_acc: 0.7436 - image_quality_output_acc: 0.5561 - age_output_acc: 0.4074 - weight_output_acc: 0.6351 - bag_output_acc: 0.6056 - footwear_output_acc: 0.6490 - pose_output_acc: 0.7253 - emotion_output_acc: 0.7160 - val_loss: 7.1341 - val_gender_output_loss: 0.5297 - val_image_quality_output_loss: 0.9653 - val_age_output_loss: 1.4081 - val_weight_output_loss: 0.9562 - val_bag_output_loss: 0.8801 - val_footwear_output_loss: 0.8096 - val_pose_output_loss: 0.6546 - val_emotion_output_loss: 0.9306 - val_gender_output_acc: 0.7243 - val_image_quality_output_acc: 0.5524 - val_age_output_acc: 0.3755 - val_weight_output_acc: 0.6406 - val_bag_output_acc: 0.5801 - val_footwear_output_acc: 0.6331 - val_pose_output_acc: 0.7152 - val_emotion_output_acc: 0.6845

Epoch 00009: val_loss improved from 7.21956 to 7.13407, saving model to /content/saved_models/VGG19_model.009.h5
Epoch 10/50

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
360/360 [==============================] - 92s 256ms/step - loss: 6.8748 - gender_output_loss: 0.4915 - image_quality_output_loss: 0.9616 - age_output_loss: 1.3668 - weight_output_loss: 0.9488 - bag_output_loss: 0.8421 - footwear_output_loss: 0.7794 - pose_output_loss: 0.6181 - emotion_output_loss: 0.8665 - gender_output_acc: 0.7658 - image_quality_output_acc: 0.5565 - age_output_acc: 0.4068 - weight_output_acc: 0.6359 - bag_output_acc: 0.6130 - footwear_output_acc: 0.6566 - pose_output_acc: 0.7503 - emotion_output_acc: 0.7159 - val_loss: 7.1094 - val_gender_output_loss: 0.5208 - val_image_quality_output_loss: 0.9684 - val_age_output_loss: 1.4106 - val_weight_output_loss: 0.9577 - val_bag_output_loss: 0.8866 - val_footwear_output_loss: 0.8127 - val_pose_output_loss: 0.6242 - val_emotion_output_loss: 0.9285 - val_gender_output_acc: 0.7384 - val_image_quality_output_acc: 0.5514 - val_age_output_acc: 0.3725 - val_weight_output_acc: 0.6401 - val_bag_output_acc: 0.5892 - val_footwear_output_acc: 0.6316 - val_pose_output_acc: 0.7364 - val_emotion_output_acc: 0.6845

Epoch 00010: val_loss improved from 7.13407 to 7.10942, saving model to /content/saved_models/VGG19_model.010.h5
Epoch 11/50

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
360/360 [==============================] - 92s 257ms/step - loss: 6.7790 - gender_output_loss: 0.4693 - image_quality_output_loss: 0.9545 - age_output_loss: 1.3605 - weight_output_loss: 0.9415 - bag_output_loss: 0.8382 - footwear_output_loss: 0.7647 - pose_output_loss: 0.5882 - emotion_output_loss: 0.8621 - gender_output_acc: 0.7720 - image_quality_output_acc: 0.5569 - age_output_acc: 0.4115 - weight_output_acc: 0.6389 - bag_output_acc: 0.6228 - footwear_output_acc: 0.6633 - pose_output_acc: 0.7613 - emotion_output_acc: 0.7159 - val_loss: 7.1040 - val_gender_output_loss: 0.5081 - val_image_quality_output_loss: 0.9636 - val_age_output_loss: 1.4136 - val_weight_output_loss: 0.9491 - val_bag_output_loss: 0.8899 - val_footwear_output_loss: 0.8259 - val_pose_output_loss: 0.6223 - val_emotion_output_loss: 0.9315 - val_gender_output_acc: 0.7384 - val_image_quality_output_acc: 0.5544 - val_age_output_acc: 0.3690 - val_weight_output_acc: 0.6411 - val_bag_output_acc: 0.5670 - val_footwear_output_acc: 0.6275 - val_pose_output_acc: 0.7314 - val_emotion_output_acc: 0.6845

Epoch 00011: val_loss improved from 7.10942 to 7.10403, saving model to /content/saved_models/VGG19_model.011.h5
Epoch 12/50

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
360/360 [==============================] - 92s 256ms/step - loss: 6.6532 - gender_output_loss: 0.4338 - image_quality_output_loss: 0.9528 - age_output_loss: 1.3482 - weight_output_loss: 0.9338 - bag_output_loss: 0.8198 - footwear_output_loss: 0.7526 - pose_output_loss: 0.5570 - emotion_output_loss: 0.8552 - gender_output_acc: 0.7970 - image_quality_output_acc: 0.5601 - age_output_acc: 0.4187 - weight_output_acc: 0.6391 - bag_output_acc: 0.6325 - footwear_output_acc: 0.6682 - pose_output_acc: 0.7705 - emotion_output_acc: 0.7168 - val_loss: 7.1381 - val_gender_output_loss: 0.5649 - val_image_quality_output_loss: 0.9633 - val_age_output_loss: 1.4134 - val_weight_output_loss: 0.9501 - val_bag_output_loss: 0.8878 - val_footwear_output_loss: 0.8037 - val_pose_output_loss: 0.6170 - val_emotion_output_loss: 0.9380 - val_gender_output_acc: 0.7334 - val_image_quality_output_acc: 0.5529 - val_age_output_acc: 0.3594 - val_weight_output_acc: 0.6436 - val_bag_output_acc: 0.5882 - val_footwear_output_acc: 0.6331 - val_pose_output_acc: 0.7434 - val_emotion_output_acc: 0.6845

Epoch 00012: val_loss did not improve from 7.10403
Epoch 13/50

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
360/360 [==============================] - 92s 256ms/step - loss: 6.5211 - gender_output_loss: 0.4021 - image_quality_output_loss: 0.9457 - age_output_loss: 1.3388 - weight_output_loss: 0.9222 - bag_output_loss: 0.8061 - footwear_output_loss: 0.7353 - pose_output_loss: 0.5227 - emotion_output_loss: 0.8483 - gender_output_acc: 0.8184 - image_quality_output_acc: 0.5615 - age_output_acc: 0.4213 - weight_output_acc: 0.6407 - bag_output_acc: 0.6438 - footwear_output_acc: 0.6791 - pose_output_acc: 0.7909 - emotion_output_acc: 0.7158 - val_loss: 7.0157 - val_gender_output_loss: 0.4856 - val_image_quality_output_loss: 0.9662 - val_age_output_loss: 1.4020 - val_weight_output_loss: 0.9540 - val_bag_output_loss: 0.8666 - val_footwear_output_loss: 0.7985 - val_pose_output_loss: 0.5991 - val_emotion_output_loss: 0.9437 - val_gender_output_acc: 0.7666 - val_image_quality_output_acc: 0.5549 - val_age_output_acc: 0.3700 - val_weight_output_acc: 0.6416 - val_bag_output_acc: 0.5998 - val_footwear_output_acc: 0.6321 - val_pose_output_acc: 0.7505 - val_emotion_output_acc: 0.6845

Epoch 00013: val_loss improved from 7.10403 to 7.01566, saving model to /content/saved_models/VGG19_model.013.h5
Epoch 14/50

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
360/360 [==============================] - 92s 256ms/step - loss: 6.3983 - gender_output_loss: 0.3677 - image_quality_output_loss: 0.9389 - age_output_loss: 1.3271 - weight_output_loss: 0.9103 - bag_output_loss: 0.7945 - footwear_output_loss: 0.7243 - pose_output_loss: 0.4946 - emotion_output_loss: 0.8410 - gender_output_acc: 0.8386 - image_quality_output_acc: 0.5652 - age_output_acc: 0.4233 - weight_output_acc: 0.6451 - bag_output_acc: 0.6556 - footwear_output_acc: 0.6813 - pose_output_acc: 0.8003 - emotion_output_acc: 0.7165 - val_loss: 7.0419 - val_gender_output_loss: 0.5000 - val_image_quality_output_loss: 0.9678 - val_age_output_loss: 1.4202 - val_weight_output_loss: 0.9440 - val_bag_output_loss: 0.8694 - val_footwear_output_loss: 0.8015 - val_pose_output_loss: 0.5910 - val_emotion_output_loss: 0.9479 - val_gender_output_acc: 0.7515 - val_image_quality_output_acc: 0.5529 - val_age_output_acc: 0.3725 - val_weight_output_acc: 0.6421 - val_bag_output_acc: 0.6114 - val_footwear_output_acc: 0.6411 - val_pose_output_acc: 0.7651 - val_emotion_output_acc: 0.6845

Epoch 00014: val_loss did not improve from 7.01566
Epoch 15/50

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
360/360 [==============================] - 92s 256ms/step - loss: 6.2364 - gender_output_loss: 0.3442 - image_quality_output_loss: 0.9318 - age_output_loss: 1.3044 - weight_output_loss: 0.8962 - bag_output_loss: 0.7710 - footwear_output_loss: 0.7022 - pose_output_loss: 0.4583 - emotion_output_loss: 0.8284 - gender_output_acc: 0.8471 - image_quality_output_acc: 0.5671 - age_output_acc: 0.4369 - weight_output_acc: 0.6479 - bag_output_acc: 0.6656 - footwear_output_acc: 0.6930 - pose_output_acc: 0.8210 - emotion_output_acc: 0.7167 - val_loss: 7.0887 - val_gender_output_loss: 0.5032 - val_image_quality_output_loss: 0.9664 - val_age_output_loss: 1.4176 - val_weight_output_loss: 0.9608 - val_bag_output_loss: 0.8673 - val_footwear_output_loss: 0.8082 - val_pose_output_loss: 0.5947 - val_emotion_output_loss: 0.9705 - val_gender_output_acc: 0.7555 - val_image_quality_output_acc: 0.5534 - val_age_output_acc: 0.3584 - val_weight_output_acc: 0.6326 - val_bag_output_acc: 0.6230 - val_footwear_output_acc: 0.6401 - val_pose_output_acc: 0.7515 - val_emotion_output_acc: 0.6845

Epoch 00015: val_loss did not improve from 7.01566
Epoch 16/50

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
360/360 [==============================] - 92s 256ms/step - loss: 6.0579 - gender_output_loss: 0.3073 - image_quality_output_loss: 0.9232 - age_output_loss: 1.2856 - weight_output_loss: 0.8785 - bag_output_loss: 0.7476 - footwear_output_loss: 0.6824 - pose_output_loss: 0.4160 - emotion_output_loss: 0.8172 - gender_output_acc: 0.8663 - image_quality_output_acc: 0.5696 - age_output_acc: 0.4437 - weight_output_acc: 0.6555 - bag_output_acc: 0.6797 - footwear_output_acc: 0.7043 - pose_output_acc: 0.8379 - emotion_output_acc: 0.7180 - val_loss: 7.2106 - val_gender_output_loss: 0.5340 - val_image_quality_output_loss: 0.9713 - val_age_output_loss: 1.4334 - val_weight_output_loss: 0.9869 - val_bag_output_loss: 0.8946 - val_footwear_output_loss: 0.8176 - val_pose_output_loss: 0.6268 - val_emotion_output_loss: 0.9460 - val_gender_output_acc: 0.7732 - val_image_quality_output_acc: 0.5559 - val_age_output_acc: 0.3639 - val_weight_output_acc: 0.6114 - val_bag_output_acc: 0.6013 - val_footwear_output_acc: 0.6346 - val_pose_output_acc: 0.7525 - val_emotion_output_acc: 0.6830

Epoch 00016: val_loss did not improve from 7.01566
Epoch 17/50

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
360/360 [==============================] - 92s 256ms/step - loss: 5.8880 - gender_output_loss: 0.2815 - image_quality_output_loss: 0.9144 - age_output_loss: 1.2598 - weight_output_loss: 0.8569 - bag_output_loss: 0.7274 - footwear_output_loss: 0.6601 - pose_output_loss: 0.3855 - emotion_output_loss: 0.8025 - gender_output_acc: 0.8808 - image_quality_output_acc: 0.5727 - age_output_acc: 0.4583 - weight_output_acc: 0.6627 - bag_output_acc: 0.6909 - footwear_output_acc: 0.7151 - pose_output_acc: 0.8507 - emotion_output_acc: 0.7186 - val_loss: 7.3775 - val_gender_output_loss: 0.5337 - val_image_quality_output_loss: 0.9920 - val_age_output_loss: 1.4362 - val_weight_output_loss: 0.9979 - val_bag_output_loss: 0.8947 - val_footwear_output_loss: 0.9131 - val_pose_output_loss: 0.6458 - val_emotion_output_loss: 0.9641 - val_gender_output_acc: 0.7621 - val_image_quality_output_acc: 0.5242 - val_age_output_acc: 0.3765 - val_weight_output_acc: 0.6094 - val_bag_output_acc: 0.5993 - val_footwear_output_acc: 0.6119 - val_pose_output_acc: 0.7409 - val_emotion_output_acc: 0.6850

Epoch 00017: val_loss did not improve from 7.01566
Epoch 18/50

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
360/360 [==============================] - 92s 257ms/step - loss: 5.6556 - gender_output_loss: 0.2481 - image_quality_output_loss: 0.8997 - age_output_loss: 1.2202 - weight_output_loss: 0.8315 - bag_output_loss: 0.6926 - footwear_output_loss: 0.6301 - pose_output_loss: 0.3448 - emotion_output_loss: 0.7887 - gender_output_acc: 0.8982 - image_quality_output_acc: 0.5844 - age_output_acc: 0.4758 - weight_output_acc: 0.6694 - bag_output_acc: 0.7129 - footwear_output_acc: 0.7316 - pose_output_acc: 0.8669 - emotion_output_acc: 0.7216 - val_loss: 7.5876 - val_gender_output_loss: 0.6246 - val_image_quality_output_loss: 0.9805 - val_age_output_loss: 1.5000 - val_weight_output_loss: 0.9770 - val_bag_output_loss: 0.9231 - val_footwear_output_loss: 0.9119 - val_pose_output_loss: 0.6795 - val_emotion_output_loss: 0.9910 - val_gender_output_acc: 0.7671 - val_image_quality_output_acc: 0.5449 - val_age_output_acc: 0.3367 - val_weight_output_acc: 0.6280 - val_bag_output_acc: 0.6003 - val_footwear_output_acc: 0.6210 - val_pose_output_acc: 0.7485 - val_emotion_output_acc: 0.6850

Epoch 00018: val_loss did not improve from 7.01566
Epoch 19/50

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
360/360 [==============================] - 92s 257ms/step - loss: 5.3994 - gender_output_loss: 0.2147 - image_quality_output_loss: 0.8757 - age_output_loss: 1.1869 - weight_output_loss: 0.7983 - bag_output_loss: 0.6616 - footwear_output_loss: 0.5985 - pose_output_loss: 0.3029 - emotion_output_loss: 0.7609 - gender_output_acc: 0.9139 - image_quality_output_acc: 0.5958 - age_output_acc: 0.4946 - weight_output_acc: 0.6820 - bag_output_acc: 0.7220 - footwear_output_acc: 0.7444 - pose_output_acc: 0.8818 - emotion_output_acc: 0.7284 - val_loss: 7.5287 - val_gender_output_loss: 0.5500 - val_image_quality_output_loss: 0.9980 - val_age_output_loss: 1.4658 - val_weight_output_loss: 1.0472 - val_bag_output_loss: 0.8987 - val_footwear_output_loss: 0.9332 - val_pose_output_loss: 0.6784 - val_emotion_output_loss: 0.9575 - val_gender_output_acc: 0.7727 - val_image_quality_output_acc: 0.5242 - val_age_output_acc: 0.3604 - val_weight_output_acc: 0.5731 - val_bag_output_acc: 0.5892 - val_footwear_output_acc: 0.6134 - val_pose_output_acc: 0.7576 - val_emotion_output_acc: 0.6769

Epoch 00019: val_loss did not improve from 7.01566
Epoch 20/50

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
360/360 [==============================] - 93s 258ms/step - loss: 5.1063 - gender_output_loss: 0.1924 - image_quality_output_loss: 0.8520 - age_output_loss: 1.1279 - weight_output_loss: 0.7511 - bag_output_loss: 0.6168 - footwear_output_loss: 0.5696 - pose_output_loss: 0.2831 - emotion_output_loss: 0.7133 - gender_output_acc: 0.9221 - image_quality_output_acc: 0.6093 - age_output_acc: 0.5251 - weight_output_acc: 0.6991 - bag_output_acc: 0.7445 - footwear_output_acc: 0.7585 - pose_output_acc: 0.8882 - emotion_output_acc: 0.7417 - val_loss: 7.9998 - val_gender_output_loss: 0.7206 - val_image_quality_output_loss: 1.0521 - val_age_output_loss: 1.5228 - val_weight_output_loss: 1.0308 - val_bag_output_loss: 0.9726 - val_footwear_output_loss: 0.9221 - val_pose_output_loss: 0.7779 - val_emotion_output_loss: 1.0009 - val_gender_output_acc: 0.7651 - val_image_quality_output_acc: 0.5504 - val_age_output_acc: 0.3629 - val_weight_output_acc: 0.6079 - val_bag_output_acc: 0.5958 - val_footwear_output_acc: 0.6290 - val_pose_output_acc: 0.7394 - val_emotion_output_acc: 0.6744

Epoch 00020: val_loss did not improve from 7.01566
Epoch 21/50

Epoch 00021: LearningRateScheduler setting learning rate to 0.0004065041.
360/360 [==============================] - 92s 257ms/step - loss: 4.7972 - gender_output_loss: 0.1738 - image_quality_output_loss: 0.8184 - age_output_loss: 1.0761 - weight_output_loss: 0.7024 - bag_output_loss: 0.5730 - footwear_output_loss: 0.5315 - pose_output_loss: 0.2370 - emotion_output_loss: 0.6849 - gender_output_acc: 0.9290 - image_quality_output_acc: 0.6254 - age_output_acc: 0.5523 - weight_output_acc: 0.7246 - bag_output_acc: 0.7594 - footwear_output_acc: 0.7753 - pose_output_acc: 0.9076 - emotion_output_acc: 0.7515 - val_loss: 8.2131 - val_gender_output_loss: 0.7460 - val_image_quality_output_loss: 1.0385 - val_age_output_loss: 1.5744 - val_weight_output_loss: 1.0624 - val_bag_output_loss: 0.9858 - val_footwear_output_loss: 0.9344 - val_pose_output_loss: 0.8271 - val_emotion_output_loss: 1.0444 - val_gender_output_acc: 0.7490 - val_image_quality_output_acc: 0.5302 - val_age_output_acc: 0.3634 - val_weight_output_acc: 0.6250 - val_bag_output_acc: 0.5842 - val_footwear_output_acc: 0.6205 - val_pose_output_acc: 0.7490 - val_emotion_output_acc: 0.6794

Epoch 00021: val_loss did not improve from 7.01566
Epoch 22/50

Epoch 00022: LearningRateScheduler setting learning rate to 0.000389661.
360/360 [==============================] - 93s 258ms/step - loss: 4.4243 - gender_output_loss: 0.1541 - image_quality_output_loss: 0.7752 - age_output_loss: 0.9934 - weight_output_loss: 0.6458 - bag_output_loss: 0.5153 - footwear_output_loss: 0.4847 - pose_output_loss: 0.2081 - emotion_output_loss: 0.6477 - gender_output_acc: 0.9397 - image_quality_output_acc: 0.6472 - age_output_acc: 0.5886 - weight_output_acc: 0.7467 - bag_output_acc: 0.7854 - footwear_output_acc: 0.7963 - pose_output_acc: 0.9227 - emotion_output_acc: 0.7569 - val_loss: 8.4843 - val_gender_output_loss: 0.7158 - val_image_quality_output_loss: 1.0896 - val_age_output_loss: 1.6170 - val_weight_output_loss: 1.1041 - val_bag_output_loss: 1.0571 - val_footwear_output_loss: 1.0006 - val_pose_output_loss: 0.8371 - val_emotion_output_loss: 1.0631 - val_gender_output_acc: 0.7611 - val_image_quality_output_acc: 0.5086 - val_age_output_acc: 0.3609 - val_weight_output_acc: 0.5675 - val_bag_output_acc: 0.5731 - val_footwear_output_acc: 0.6028 - val_pose_output_acc: 0.7404 - val_emotion_output_acc: 0.6144

Epoch 00022: val_loss did not improve from 7.01566
Epoch 23/50

Epoch 00023: LearningRateScheduler setting learning rate to 0.0003741581.
360/360 [==============================] - 93s 257ms/step - loss: 4.0267 - gender_output_loss: 0.1370 - image_quality_output_loss: 0.7183 - age_output_loss: 0.9174 - weight_output_loss: 0.5813 - bag_output_loss: 0.4584 - footwear_output_loss: 0.4480 - pose_output_loss: 0.1969 - emotion_output_loss: 0.5694 - gender_output_acc: 0.9475 - image_quality_output_acc: 0.6813 - age_output_acc: 0.6285 - weight_output_acc: 0.7674 - bag_output_acc: 0.8152 - footwear_output_acc: 0.8063 - pose_output_acc: 0.9278 - emotion_output_acc: 0.7868 - val_loss: 9.0572 - val_gender_output_loss: 0.7675 - val_image_quality_output_loss: 1.1315 - val_age_output_loss: 1.6840 - val_weight_output_loss: 1.1461 - val_bag_output_loss: 1.1037 - val_footwear_output_loss: 1.0374 - val_pose_output_loss: 0.8999 - val_emotion_output_loss: 1.2870 - val_gender_output_acc: 0.7495 - val_image_quality_output_acc: 0.4723 - val_age_output_acc: 0.3448 - val_weight_output_acc: 0.5731 - val_bag_output_acc: 0.5837 - val_footwear_output_acc: 0.6230 - val_pose_output_acc: 0.7334 - val_emotion_output_acc: 0.6825

Epoch 00023: val_loss did not improve from 7.01566
Epoch 24/50

Epoch 00024: LearningRateScheduler setting learning rate to 0.0003598417.
360/360 [==============================] - 93s 257ms/step - loss: 3.5546 - gender_output_loss: 0.1327 - image_quality_output_loss: 0.6626 - age_output_loss: 0.7926 - weight_output_loss: 0.5030 - bag_output_loss: 0.3940 - footwear_output_loss: 0.4010 - pose_output_loss: 0.1598 - emotion_output_loss: 0.5089 - gender_output_acc: 0.9488 - image_quality_output_acc: 0.7099 - age_output_acc: 0.6821 - weight_output_acc: 0.8014 - bag_output_acc: 0.8418 - footwear_output_acc: 0.8313 - pose_output_acc: 0.9388 - emotion_output_acc: 0.8106 - val_loss: 10.4193 - val_gender_output_loss: 0.9758 - val_image_quality_output_loss: 1.1979 - val_age_output_loss: 1.8795 - val_weight_output_loss: 1.3084 - val_bag_output_loss: 1.4226 - val_footwear_output_loss: 1.1943 - val_pose_output_loss: 1.1653 - val_emotion_output_loss: 1.2755 - val_gender_output_acc: 0.7626 - val_image_quality_output_acc: 0.4738 - val_age_output_acc: 0.3352 - val_weight_output_acc: 0.5927 - val_bag_output_acc: 0.5786 - val_footwear_output_acc: 0.6139 - val_pose_output_acc: 0.7495 - val_emotion_output_acc: 0.6366

Epoch 00024: val_loss did not improve from 7.01566
Epoch 25/50

Epoch 00025: LearningRateScheduler setting learning rate to 0.0003465804.
360/360 [==============================] - 93s 257ms/step - loss: 3.1016 - gender_output_loss: 0.1169 - image_quality_output_loss: 0.5899 - age_output_loss: 0.6923 - weight_output_loss: 0.4427 - bag_output_loss: 0.3329 - footwear_output_loss: 0.3400 - pose_output_loss: 0.1547 - emotion_output_loss: 0.4321 - gender_output_acc: 0.9551 - image_quality_output_acc: 0.7511 - age_output_acc: 0.7306 - weight_output_acc: 0.8230 - bag_output_acc: 0.8690 - footwear_output_acc: 0.8585 - pose_output_acc: 0.9430 - emotion_output_acc: 0.8411 - val_loss: 10.5004 - val_gender_output_loss: 0.9329 - val_image_quality_output_loss: 1.2841 - val_age_output_loss: 1.9664 - val_weight_output_loss: 1.3529 - val_bag_output_loss: 1.2792 - val_footwear_output_loss: 1.2775 - val_pose_output_loss: 1.0505 - val_emotion_output_loss: 1.3569 - val_gender_output_acc: 0.7576 - val_image_quality_output_acc: 0.4990 - val_age_output_acc: 0.3322 - val_weight_output_acc: 0.5706 - val_bag_output_acc: 0.5822 - val_footwear_output_acc: 0.5938 - val_pose_output_acc: 0.7369 - val_emotion_output_acc: 0.6245

Epoch 00025: val_loss did not improve from 7.01566
Epoch 26/50

Epoch 00026: LearningRateScheduler setting learning rate to 0.0003342618.
360/360 [==============================] - 92s 257ms/step - loss: 2.6718 - gender_output_loss: 0.1082 - image_quality_output_loss: 0.5089 - age_output_loss: 0.5859 - weight_output_loss: 0.3739 - bag_output_loss: 0.2954 - footwear_output_loss: 0.2996 - pose_output_loss: 0.1319 - emotion_output_loss: 0.3680 - gender_output_acc: 0.9589 - image_quality_output_acc: 0.7913 - age_output_acc: 0.7771 - weight_output_acc: 0.8543 - bag_output_acc: 0.8838 - footwear_output_acc: 0.8824 - pose_output_acc: 0.9507 - emotion_output_acc: 0.8636 - val_loss: 11.4338 - val_gender_output_loss: 0.9089 - val_image_quality_output_loss: 1.3307 - val_age_output_loss: 2.0732 - val_weight_output_loss: 1.4017 - val_bag_output_loss: 1.5958 - val_footwear_output_loss: 1.3643 - val_pose_output_loss: 1.1597 - val_emotion_output_loss: 1.5996 - val_gender_output_acc: 0.7520 - val_image_quality_output_acc: 0.4667 - val_age_output_acc: 0.3327 - val_weight_output_acc: 0.6003 - val_bag_output_acc: 0.5862 - val_footwear_output_acc: 0.6079 - val_pose_output_acc: 0.7293 - val_emotion_output_acc: 0.6668

Epoch 00026: val_loss did not improve from 7.01566
Epoch 27/50

Epoch 00027: LearningRateScheduler setting learning rate to 0.0003227889.
360/360 [==============================] - 92s 257ms/step - loss: 2.2666 - gender_output_loss: 0.0951 - image_quality_output_loss: 0.4402 - age_output_loss: 0.4904 - weight_output_loss: 0.3168 - bag_output_loss: 0.2480 - footwear_output_loss: 0.2532 - pose_output_loss: 0.1218 - emotion_output_loss: 0.3010 - gender_output_acc: 0.9624 - image_quality_output_acc: 0.8188 - age_output_acc: 0.8153 - weight_output_acc: 0.8794 - bag_output_acc: 0.9038 - footwear_output_acc: 0.9009 - pose_output_acc: 0.9560 - emotion_output_acc: 0.8870 - val_loss: 12.0817 - val_gender_output_loss: 1.0841 - val_image_quality_output_loss: 1.4280 - val_age_output_loss: 2.3924 - val_weight_output_loss: 1.6300 - val_bag_output_loss: 1.4770 - val_footwear_output_loss: 1.3769 - val_pose_output_loss: 1.1866 - val_emotion_output_loss: 1.5067 - val_gender_output_acc: 0.7545 - val_image_quality_output_acc: 0.5126 - val_age_output_acc: 0.3327 - val_weight_output_acc: 0.5943 - val_bag_output_acc: 0.5655 - val_footwear_output_acc: 0.6225 - val_pose_output_acc: 0.7369 - val_emotion_output_acc: 0.5746

Epoch 00027: val_loss did not improve from 7.01566
Epoch 28/50

Epoch 00028: LearningRateScheduler setting learning rate to 0.0003120774.
360/360 [==============================] - 93s 257ms/step - loss: 1.8842 - gender_output_loss: 0.0857 - image_quality_output_loss: 0.3569 - age_output_loss: 0.4037 - weight_output_loss: 0.2665 - bag_output_loss: 0.2034 - footwear_output_loss: 0.2173 - pose_output_loss: 0.1038 - emotion_output_loss: 0.2469 - gender_output_acc: 0.9679 - image_quality_output_acc: 0.8580 - age_output_acc: 0.8488 - weight_output_acc: 0.8987 - bag_output_acc: 0.9213 - footwear_output_acc: 0.9133 - pose_output_acc: 0.9623 - emotion_output_acc: 0.9101 - val_loss: 14.0306 - val_gender_output_loss: 1.1661 - val_image_quality_output_loss: 1.6349 - val_age_output_loss: 2.7428 - val_weight_output_loss: 1.8094 - val_bag_output_loss: 1.8066 - val_footwear_output_loss: 1.5673 - val_pose_output_loss: 1.3837 - val_emotion_output_loss: 1.9200 - val_gender_output_acc: 0.7545 - val_image_quality_output_acc: 0.4446 - val_age_output_acc: 0.3402 - val_weight_output_acc: 0.5181 - val_bag_output_acc: 0.5932 - val_footwear_output_acc: 0.6064 - val_pose_output_acc: 0.7273 - val_emotion_output_acc: 0.6416

Epoch 00028: val_loss did not improve from 7.01566
Epoch 29/50

Epoch 00029: LearningRateScheduler setting learning rate to 0.000302054.
360/360 [==============================] - 93s 258ms/step - loss: 1.5578 - gender_output_loss: 0.0754 - image_quality_output_loss: 0.2910 - age_output_loss: 0.3278 - weight_output_loss: 0.2226 - bag_output_loss: 0.1759 - footwear_output_loss: 0.1709 - pose_output_loss: 0.0819 - emotion_output_loss: 0.2122 - gender_output_acc: 0.9736 - image_quality_output_acc: 0.8872 - age_output_acc: 0.8771 - weight_output_acc: 0.9147 - bag_output_acc: 0.9345 - footwear_output_acc: 0.9345 - pose_output_acc: 0.9731 - emotion_output_acc: 0.9225 - val_loss: 14.3383 - val_gender_output_loss: 1.1387 - val_image_quality_output_loss: 1.7570 - val_age_output_loss: 2.7775 - val_weight_output_loss: 1.8202 - val_bag_output_loss: 1.8637 - val_footwear_output_loss: 1.6820 - val_pose_output_loss: 1.4637 - val_emotion_output_loss: 1.8355 - val_gender_output_acc: 0.7596 - val_image_quality_output_acc: 0.4536 - val_age_output_acc: 0.3357 - val_weight_output_acc: 0.5539 - val_bag_output_acc: 0.5877 - val_footwear_output_acc: 0.6079 - val_pose_output_acc: 0.7349 - val_emotion_output_acc: 0.6179

Epoch 00029: val_loss did not improve from 7.01566
Epoch 30/50

Epoch 00030: LearningRateScheduler setting learning rate to 0.0002926544.
360/360 [==============================] - 93s 258ms/step - loss: 1.3134 - gender_output_loss: 0.0655 - image_quality_output_loss: 0.2412 - age_output_loss: 0.2732 - weight_output_loss: 0.1816 - bag_output_loss: 0.1431 - footwear_output_loss: 0.1522 - pose_output_loss: 0.0804 - emotion_output_loss: 0.1763 - gender_output_acc: 0.9773 - image_quality_output_acc: 0.9094 - age_output_acc: 0.9023 - weight_output_acc: 0.9325 - bag_output_acc: 0.9497 - footwear_output_acc: 0.9429 - pose_output_acc: 0.9712 - emotion_output_acc: 0.9366 - val_loss: 15.1764 - val_gender_output_loss: 1.1725 - val_image_quality_output_loss: 1.9880 - val_age_output_loss: 2.8904 - val_weight_output_loss: 1.9486 - val_bag_output_loss: 2.0144 - val_footwear_output_loss: 1.6863 - val_pose_output_loss: 1.4476 - val_emotion_output_loss: 2.0286 - val_gender_output_acc: 0.7500 - val_image_quality_output_acc: 0.5000 - val_age_output_acc: 0.3211 - val_weight_output_acc: 0.5776 - val_bag_output_acc: 0.5922 - val_footwear_output_acc: 0.6028 - val_pose_output_acc: 0.7414 - val_emotion_output_acc: 0.6295

Epoch 00030: val_loss did not improve from 7.01566
Epoch 31/50

Epoch 00031: LearningRateScheduler setting learning rate to 0.0002838221.
360/360 [==============================] - 93s 257ms/step - loss: 1.0840 - gender_output_loss: 0.0510 - image_quality_output_loss: 0.2067 - age_output_loss: 0.2198 - weight_output_loss: 0.1565 - bag_output_loss: 0.1222 - footwear_output_loss: 0.1208 - pose_output_loss: 0.0714 - emotion_output_loss: 0.1356 - gender_output_acc: 0.9827 - image_quality_output_acc: 0.9229 - age_output_acc: 0.9220 - weight_output_acc: 0.9413 - bag_output_acc: 0.9551 - footwear_output_acc: 0.9561 - pose_output_acc: 0.9755 - emotion_output_acc: 0.9517 - val_loss: 16.2825 - val_gender_output_loss: 1.3558 - val_image_quality_output_loss: 1.9668 - val_age_output_loss: 3.0523 - val_weight_output_loss: 2.0779 - val_bag_output_loss: 2.2654 - val_footwear_output_loss: 1.9570 - val_pose_output_loss: 1.5804 - val_emotion_output_loss: 2.0270 - val_gender_output_acc: 0.7611 - val_image_quality_output_acc: 0.4677 - val_age_output_acc: 0.3044 - val_weight_output_acc: 0.5433 - val_bag_output_acc: 0.5912 - val_footwear_output_acc: 0.6154 - val_pose_output_acc: 0.7500 - val_emotion_output_acc: 0.6190

Epoch 00031: val_loss did not improve from 7.01566
Epoch 32/50

Epoch 00032: LearningRateScheduler setting learning rate to 0.0002755074.
360/360 [==============================] - 92s 256ms/step - loss: 0.9471 - gender_output_loss: 0.0515 - image_quality_output_loss: 0.1721 - age_output_loss: 0.1934 - weight_output_loss: 0.1228 - bag_output_loss: 0.1007 - footwear_output_loss: 0.1228 - pose_output_loss: 0.0597 - emotion_output_loss: 0.1241 - gender_output_acc: 0.9827 - image_quality_output_acc: 0.9367 - age_output_acc: 0.9328 - weight_output_acc: 0.9549 - bag_output_acc: 0.9631 - footwear_output_acc: 0.9552 - pose_output_acc: 0.9780 - emotion_output_acc: 0.9572 - val_loss: 17.2615 - val_gender_output_loss: 1.2505 - val_image_quality_output_loss: 2.1087 - val_age_output_loss: 3.1760 - val_weight_output_loss: 2.3783 - val_bag_output_loss: 2.4156 - val_footwear_output_loss: 2.1048 - val_pose_output_loss: 1.5819 - val_emotion_output_loss: 2.2456 - val_gender_output_acc: 0.7636 - val_image_quality_output_acc: 0.4587 - val_age_output_acc: 0.3120 - val_weight_output_acc: 0.5685 - val_bag_output_acc: 0.5862 - val_footwear_output_acc: 0.6069 - val_pose_output_acc: 0.7465 - val_emotion_output_acc: 0.6190

Epoch 00032: val_loss did not improve from 7.01566
Epoch 33/50

Epoch 00033: LearningRateScheduler setting learning rate to 0.000267666.
360/360 [==============================] - 93s 257ms/step - loss: 0.7839 - gender_output_loss: 0.0493 - image_quality_output_loss: 0.1375 - age_output_loss: 0.1596 - weight_output_loss: 0.1071 - bag_output_loss: 0.0897 - footwear_output_loss: 0.1009 - pose_output_loss: 0.0418 - emotion_output_loss: 0.0981 - gender_output_acc: 0.9825 - image_quality_output_acc: 0.9496 - age_output_acc: 0.9444 - weight_output_acc: 0.9630 - bag_output_acc: 0.9686 - footwear_output_acc: 0.9622 - pose_output_acc: 0.9864 - emotion_output_acc: 0.9660 - val_loss: 16.7510 - val_gender_output_loss: 1.1534 - val_image_quality_output_loss: 2.1496 - val_age_output_loss: 3.3033 - val_weight_output_loss: 2.2565 - val_bag_output_loss: 2.1992 - val_footwear_output_loss: 1.9948 - val_pose_output_loss: 1.5056 - val_emotion_output_loss: 2.1885 - val_gender_output_acc: 0.7606 - val_image_quality_output_acc: 0.4824 - val_age_output_acc: 0.3296 - val_weight_output_acc: 0.5565 - val_bag_output_acc: 0.5852 - val_footwear_output_acc: 0.6069 - val_pose_output_acc: 0.7288 - val_emotion_output_acc: 0.5857

Epoch 00033: val_loss did not improve from 7.01566
Epoch 34/50

Epoch 00034: LearningRateScheduler setting learning rate to 0.0002602585.
360/360 [==============================] - 93s 257ms/step - loss: 0.6561 - gender_output_loss: 0.0330 - image_quality_output_loss: 0.1100 - age_output_loss: 0.1266 - weight_output_loss: 0.0958 - bag_output_loss: 0.0828 - footwear_output_loss: 0.0787 - pose_output_loss: 0.0517 - emotion_output_loss: 0.0776 - gender_output_acc: 0.9866 - image_quality_output_acc: 0.9585 - age_output_acc: 0.9566 - weight_output_acc: 0.9674 - bag_output_acc: 0.9696 - footwear_output_acc: 0.9736 - pose_output_acc: 0.9839 - emotion_output_acc: 0.9726 - val_loss: 20.1623 - val_gender_output_loss: 1.5224 - val_image_quality_output_loss: 2.4417 - val_age_output_loss: 3.8647 - val_weight_output_loss: 2.7417 - val_bag_output_loss: 2.7872 - val_footwear_output_loss: 2.2498 - val_pose_output_loss: 1.8321 - val_emotion_output_loss: 2.7227 - val_gender_output_acc: 0.7550 - val_image_quality_output_acc: 0.4713 - val_age_output_acc: 0.3125 - val_weight_output_acc: 0.5565 - val_bag_output_acc: 0.6043 - val_footwear_output_acc: 0.6205 - val_pose_output_acc: 0.7576 - val_emotion_output_acc: 0.6396

Epoch 00034: val_loss did not improve from 7.01566
Epoch 35/50

Epoch 00035: LearningRateScheduler setting learning rate to 0.00025325.
360/360 [==============================] - 93s 257ms/step - loss: 0.5953 - gender_output_loss: 0.0387 - image_quality_output_loss: 0.0973 - age_output_loss: 0.1255 - weight_output_loss: 0.0838 - bag_output_loss: 0.0691 - footwear_output_loss: 0.0743 - pose_output_loss: 0.0384 - emotion_output_loss: 0.0681 - gender_output_acc: 0.9866 - image_quality_output_acc: 0.9643 - age_output_acc: 0.9566 - weight_output_acc: 0.9716 - bag_output_acc: 0.9756 - footwear_output_acc: 0.9740 - pose_output_acc: 0.9872 - emotion_output_acc: 0.9761 - val_loss: 19.5093 - val_gender_output_loss: 1.4242 - val_image_quality_output_loss: 2.4115 - val_age_output_loss: 3.6071 - val_weight_output_loss: 2.6244 - val_bag_output_loss: 2.6037 - val_footwear_output_loss: 2.3175 - val_pose_output_loss: 1.7660 - val_emotion_output_loss: 2.7548 - val_gender_output_acc: 0.7646 - val_image_quality_output_acc: 0.4541 - val_age_output_acc: 0.3327 - val_weight_output_acc: 0.5892 - val_bag_output_acc: 0.5842 - val_footwear_output_acc: 0.6179 - val_pose_output_acc: 0.7475 - val_emotion_output_acc: 0.6603

Epoch 00035: val_loss did not improve from 7.01566
Epoch 36/50

Epoch 00036: LearningRateScheduler setting learning rate to 0.0002466091.
360/360 [==============================] - 93s 257ms/step - loss: 0.5090 - gender_output_loss: 0.0280 - image_quality_output_loss: 0.0970 - age_output_loss: 0.1030 - weight_output_loss: 0.0671 - bag_output_loss: 0.0574 - footwear_output_loss: 0.0625 - pose_output_loss: 0.0328 - emotion_output_loss: 0.0612 - gender_output_acc: 0.9894 - image_quality_output_acc: 0.9643 - age_output_acc: 0.9645 - weight_output_acc: 0.9764 - bag_output_acc: 0.9806 - footwear_output_acc: 0.9783 - pose_output_acc: 0.9893 - emotion_output_acc: 0.9777 - val_loss: 19.6606 - val_gender_output_loss: 1.4227 - val_image_quality_output_loss: 2.5803 - val_age_output_loss: 3.8391 - val_weight_output_loss: 2.6473 - val_bag_output_loss: 2.5424 - val_footwear_output_loss: 2.2155 - val_pose_output_loss: 1.6937 - val_emotion_output_loss: 2.7195 - val_gender_output_acc: 0.7560 - val_image_quality_output_acc: 0.4783 - val_age_output_acc: 0.3367 - val_weight_output_acc: 0.5852 - val_bag_output_acc: 0.5806 - val_footwear_output_acc: 0.6114 - val_pose_output_acc: 0.7460 - val_emotion_output_acc: 0.6562

Epoch 00036: val_loss did not improve from 7.01566
Epoch 37/50

Epoch 00037: LearningRateScheduler setting learning rate to 0.0002403076.
360/360 [==============================] - 92s 256ms/step - loss: 0.4343 - gender_output_loss: 0.0245 - image_quality_output_loss: 0.0782 - age_output_loss: 0.0876 - weight_output_loss: 0.0534 - bag_output_loss: 0.0576 - footwear_output_loss: 0.0573 - pose_output_loss: 0.0300 - emotion_output_loss: 0.0455 - gender_output_acc: 0.9913 - image_quality_output_acc: 0.9709 - age_output_acc: 0.9689 - weight_output_acc: 0.9815 - bag_output_acc: 0.9799 - footwear_output_acc: 0.9792 - pose_output_acc: 0.9896 - emotion_output_acc: 0.9835 - val_loss: 20.6416 - val_gender_output_loss: 1.4613 - val_image_quality_output_loss: 2.6735 - val_age_output_loss: 4.2468 - val_weight_output_loss: 2.8033 - val_bag_output_loss: 2.6058 - val_footwear_output_loss: 2.3226 - val_pose_output_loss: 1.8355 - val_emotion_output_loss: 2.6929 - val_gender_output_acc: 0.7606 - val_image_quality_output_acc: 0.4940 - val_age_output_acc: 0.3483 - val_weight_output_acc: 0.5731 - val_bag_output_acc: 0.5766 - val_footwear_output_acc: 0.6003 - val_pose_output_acc: 0.7308 - val_emotion_output_acc: 0.6265

Epoch 00037: val_loss did not improve from 7.01566
Epoch 38/50

Epoch 00038: LearningRateScheduler setting learning rate to 0.0002343201.
360/360 [==============================] - 93s 257ms/step - loss: 0.3814 - gender_output_loss: 0.0210 - image_quality_output_loss: 0.0622 - age_output_loss: 0.0765 - weight_output_loss: 0.0520 - bag_output_loss: 0.0445 - footwear_output_loss: 0.0514 - pose_output_loss: 0.0238 - emotion_output_loss: 0.0500 - gender_output_acc: 0.9924 - image_quality_output_acc: 0.9782 - age_output_acc: 0.9741 - weight_output_acc: 0.9818 - bag_output_acc: 0.9844 - footwear_output_acc: 0.9816 - pose_output_acc: 0.9911 - emotion_output_acc: 0.9827 - val_loss: 22.4550 - val_gender_output_loss: 1.6217 - val_image_quality_output_loss: 3.0716 - val_age_output_loss: 4.2126 - val_weight_output_loss: 3.1490 - val_bag_output_loss: 2.8658 - val_footwear_output_loss: 2.5622 - val_pose_output_loss: 2.1470 - val_emotion_output_loss: 2.8251 - val_gender_output_acc: 0.7656 - val_image_quality_output_acc: 0.4849 - val_age_output_acc: 0.3266 - val_weight_output_acc: 0.5857 - val_bag_output_acc: 0.5827 - val_footwear_output_acc: 0.6149 - val_pose_output_acc: 0.7480 - val_emotion_output_acc: 0.5791

Epoch 00038: val_loss did not improve from 7.01566
Epoch 39/50

Epoch 00039: LearningRateScheduler setting learning rate to 0.0002286237.
360/360 [==============================] - 92s 257ms/step - loss: 0.3440 - gender_output_loss: 0.0236 - image_quality_output_loss: 0.0591 - age_output_loss: 0.0659 - weight_output_loss: 0.0491 - bag_output_loss: 0.0377 - footwear_output_loss: 0.0402 - pose_output_loss: 0.0225 - emotion_output_loss: 0.0459 - gender_output_acc: 0.9918 - image_quality_output_acc: 0.9786 - age_output_acc: 0.9787 - weight_output_acc: 0.9820 - bag_output_acc: 0.9869 - footwear_output_acc: 0.9864 - pose_output_acc: 0.9919 - emotion_output_acc: 0.9854 - val_loss: 21.7395 - val_gender_output_loss: 1.6211 - val_image_quality_output_loss: 2.7272 - val_age_output_loss: 4.2155 - val_weight_output_loss: 2.9555 - val_bag_output_loss: 2.7833 - val_footwear_output_loss: 2.4840 - val_pose_output_loss: 1.8977 - val_emotion_output_loss: 3.0552 - val_gender_output_acc: 0.7641 - val_image_quality_output_acc: 0.4521 - val_age_output_acc: 0.3125 - val_weight_output_acc: 0.5963 - val_bag_output_acc: 0.5761 - val_footwear_output_acc: 0.5887 - val_pose_output_acc: 0.7470 - val_emotion_output_acc: 0.6442

Epoch 00039: val_loss did not improve from 7.01566
Epoch 40/50

Epoch 00040: LearningRateScheduler setting learning rate to 0.0002231977.
360/360 [==============================] - 92s 257ms/step - loss: 0.3114 - gender_output_loss: 0.0200 - image_quality_output_loss: 0.0479 - age_output_loss: 0.0589 - weight_output_loss: 0.0452 - bag_output_loss: 0.0402 - footwear_output_loss: 0.0418 - pose_output_loss: 0.0254 - emotion_output_loss: 0.0319 - gender_output_acc: 0.9937 - image_quality_output_acc: 0.9843 - age_output_acc: 0.9804 - weight_output_acc: 0.9852 - bag_output_acc: 0.9870 - footwear_output_acc: 0.9863 - pose_output_acc: 0.9927 - emotion_output_acc: 0.9899 - val_loss: 23.4096 - val_gender_output_loss: 1.6592 - val_image_quality_output_loss: 3.1539 - val_age_output_loss: 4.5458 - val_weight_output_loss: 3.3358 - val_bag_output_loss: 2.9886 - val_footwear_output_loss: 2.6885 - val_pose_output_loss: 1.9946 - val_emotion_output_loss: 3.0432 - val_gender_output_acc: 0.7591 - val_image_quality_output_acc: 0.4652 - val_age_output_acc: 0.3014 - val_weight_output_acc: 0.5988 - val_bag_output_acc: 0.5751 - val_footwear_output_acc: 0.6104 - val_pose_output_acc: 0.7465 - val_emotion_output_acc: 0.6290

Epoch 00040: val_loss did not improve from 7.01566
Epoch 41/50

Epoch 00041: LearningRateScheduler setting learning rate to 0.0002180233.
360/360 [==============================] - 92s 257ms/step - loss: 0.2552 - gender_output_loss: 0.0122 - image_quality_output_loss: 0.0433 - age_output_loss: 0.0528 - weight_output_loss: 0.0363 - bag_output_loss: 0.0299 - footwear_output_loss: 0.0273 - pose_output_loss: 0.0208 - emotion_output_loss: 0.0326 - gender_output_acc: 0.9960 - image_quality_output_acc: 0.9846 - age_output_acc: 0.9829 - weight_output_acc: 0.9876 - bag_output_acc: 0.9889 - footwear_output_acc: 0.9898 - pose_output_acc: 0.9925 - emotion_output_acc: 0.9878 - val_loss: 23.1209 - val_gender_output_loss: 1.6881 - val_image_quality_output_loss: 3.1586 - val_age_output_loss: 4.6520 - val_weight_output_loss: 3.0918 - val_bag_output_loss: 2.9048 - val_footwear_output_loss: 2.5858 - val_pose_output_loss: 1.9785 - val_emotion_output_loss: 3.0614 - val_gender_output_acc: 0.7606 - val_image_quality_output_acc: 0.4693 - val_age_output_acc: 0.3317 - val_weight_output_acc: 0.5459 - val_bag_output_acc: 0.5811 - val_footwear_output_acc: 0.6094 - val_pose_output_acc: 0.7389 - val_emotion_output_acc: 0.6386

Epoch 00041: val_loss did not improve from 7.01566
Epoch 42/50

Epoch 00042: LearningRateScheduler setting learning rate to 0.0002130833.
360/360 [==============================] - 93s 257ms/step - loss: 0.2522 - gender_output_loss: 0.0122 - image_quality_output_loss: 0.0421 - age_output_loss: 0.0503 - weight_output_loss: 0.0402 - bag_output_loss: 0.0298 - footwear_output_loss: 0.0257 - pose_output_loss: 0.0243 - emotion_output_loss: 0.0275 - gender_output_acc: 0.9951 - image_quality_output_acc: 0.9854 - age_output_acc: 0.9818 - weight_output_acc: 0.9872 - bag_output_acc: 0.9898 - footwear_output_acc: 0.9911 - pose_output_acc: 0.9909 - emotion_output_acc: 0.9900 - val_loss: 23.2911 - val_gender_output_loss: 1.7423 - val_image_quality_output_loss: 3.1354 - val_age_output_loss: 4.5580 - val_weight_output_loss: 3.1641 - val_bag_output_loss: 3.0420 - val_footwear_output_loss: 2.5942 - val_pose_output_loss: 2.0599 - val_emotion_output_loss: 2.9952 - val_gender_output_acc: 0.7596 - val_image_quality_output_acc: 0.4632 - val_age_output_acc: 0.3075 - val_weight_output_acc: 0.5756 - val_bag_output_acc: 0.5922 - val_footwear_output_acc: 0.6200 - val_pose_output_acc: 0.7465 - val_emotion_output_acc: 0.6179

Epoch 00042: val_loss did not improve from 7.01566
Epoch 43/50

Epoch 00043: LearningRateScheduler setting learning rate to 0.0002083623.
360/360 [==============================] - 92s 257ms/step - loss: 0.2025 - gender_output_loss: 0.0106 - image_quality_output_loss: 0.0338 - age_output_loss: 0.0384 - weight_output_loss: 0.0317 - bag_output_loss: 0.0225 - footwear_output_loss: 0.0258 - pose_output_loss: 0.0125 - emotion_output_loss: 0.0271 - gender_output_acc: 0.9964 - image_quality_output_acc: 0.9881 - age_output_acc: 0.9874 - weight_output_acc: 0.9894 - bag_output_acc: 0.9939 - footwear_output_acc: 0.9911 - pose_output_acc: 0.9957 - emotion_output_acc: 0.9917 - val_loss: 26.4530 - val_gender_output_loss: 1.9709 - val_image_quality_output_loss: 3.6008 - val_age_output_loss: 5.4414 - val_weight_output_loss: 3.5195 - val_bag_output_loss: 3.4636 - val_footwear_output_loss: 2.9421 - val_pose_output_loss: 2.2455 - val_emotion_output_loss: 3.2691 - val_gender_output_acc: 0.7550 - val_image_quality_output_acc: 0.4849 - val_age_output_acc: 0.3332 - val_weight_output_acc: 0.5857 - val_bag_output_acc: 0.5847 - val_footwear_output_acc: 0.5958 - val_pose_output_acc: 0.7384 - val_emotion_output_acc: 0.6089

Epoch 00043: val_loss did not improve from 7.01566
Epoch 44/50

Epoch 00044: LearningRateScheduler setting learning rate to 0.0002038459.
360/360 [==============================] - 93s 258ms/step - loss: 0.1947 - gender_output_loss: 0.0131 - image_quality_output_loss: 0.0352 - age_output_loss: 0.0378 - weight_output_loss: 0.0239 - bag_output_loss: 0.0287 - footwear_output_loss: 0.0239 - pose_output_loss: 0.0096 - emotion_output_loss: 0.0226 - gender_output_acc: 0.9953 - image_quality_output_acc: 0.9870 - age_output_acc: 0.9881 - weight_output_acc: 0.9926 - bag_output_acc: 0.9914 - footwear_output_acc: 0.9922 - pose_output_acc: 0.9969 - emotion_output_acc: 0.9919 - val_loss: 26.1787 - val_gender_output_loss: 1.8940 - val_image_quality_output_loss: 3.6168 - val_age_output_loss: 5.2386 - val_weight_output_loss: 3.5125 - val_bag_output_loss: 3.3151 - val_footwear_output_loss: 2.8706 - val_pose_output_loss: 2.1398 - val_emotion_output_loss: 3.5912 - val_gender_output_acc: 0.7560 - val_image_quality_output_acc: 0.4965 - val_age_output_acc: 0.3427 - val_weight_output_acc: 0.5912 - val_bag_output_acc: 0.5912 - val_footwear_output_acc: 0.6195 - val_pose_output_acc: 0.7434 - val_emotion_output_acc: 0.6452

Epoch 00044: val_loss did not improve from 7.01566
Epoch 45/50

Epoch 00045: LearningRateScheduler setting learning rate to 0.0001995211.
360/360 [==============================] - 93s 257ms/step - loss: 0.1484 - gender_output_loss: 0.0084 - image_quality_output_loss: 0.0262 - age_output_loss: 0.0258 - weight_output_loss: 0.0188 - bag_output_loss: 0.0180 - footwear_output_loss: 0.0229 - pose_output_loss: 0.0100 - emotion_output_loss: 0.0184 - gender_output_acc: 0.9976 - image_quality_output_acc: 0.9903 - age_output_acc: 0.9911 - weight_output_acc: 0.9935 - bag_output_acc: 0.9929 - footwear_output_acc: 0.9933 - pose_output_acc: 0.9970 - emotion_output_acc: 0.9937 - val_loss: 25.6361 - val_gender_output_loss: 1.8629 - val_image_quality_output_loss: 3.5380 - val_age_output_loss: 5.0441 - val_weight_output_loss: 3.4318 - val_bag_output_loss: 3.3367 - val_footwear_output_loss: 2.8873 - val_pose_output_loss: 2.2346 - val_emotion_output_loss: 3.3007 - val_gender_output_acc: 0.7641 - val_image_quality_output_acc: 0.4864 - val_age_output_acc: 0.3251 - val_weight_output_acc: 0.5675 - val_bag_output_acc: 0.5766 - val_footwear_output_acc: 0.6084 - val_pose_output_acc: 0.7525 - val_emotion_output_acc: 0.6154

Epoch 00045: val_loss did not improve from 7.01566
Epoch 46/50

Epoch 00046: LearningRateScheduler setting learning rate to 0.0001953761.
360/360 [==============================] - 93s 257ms/step - loss: 0.1448 - gender_output_loss: 0.0079 - image_quality_output_loss: 0.0230 - age_output_loss: 0.0312 - weight_output_loss: 0.0216 - bag_output_loss: 0.0173 - footwear_output_loss: 0.0204 - pose_output_loss: 0.0082 - emotion_output_loss: 0.0151 - gender_output_acc: 0.9967 - image_quality_output_acc: 0.9924 - age_output_acc: 0.9899 - weight_output_acc: 0.9929 - bag_output_acc: 0.9944 - footwear_output_acc: 0.9940 - pose_output_acc: 0.9971 - emotion_output_acc: 0.9953 - val_loss: 25.7499 - val_gender_output_loss: 1.8262 - val_image_quality_output_loss: 3.4508 - val_age_output_loss: 4.9619 - val_weight_output_loss: 3.4195 - val_bag_output_loss: 3.3771 - val_footwear_output_loss: 3.0046 - val_pose_output_loss: 2.2422 - val_emotion_output_loss: 3.4677 - val_gender_output_acc: 0.7611 - val_image_quality_output_acc: 0.4602 - val_age_output_acc: 0.3317 - val_weight_output_acc: 0.5736 - val_bag_output_acc: 0.5953 - val_footwear_output_acc: 0.6094 - val_pose_output_acc: 0.7369 - val_emotion_output_acc: 0.6401

Epoch 00046: val_loss did not improve from 7.01566
Epoch 47/50

Epoch 00047: LearningRateScheduler setting learning rate to 0.0001913998.
360/360 [==============================] - 93s 257ms/step - loss: 0.1227 - gender_output_loss: 0.0069 - image_quality_output_loss: 0.0186 - age_output_loss: 0.0296 - weight_output_loss: 0.0142 - bag_output_loss: 0.0133 - footwear_output_loss: 0.0150 - pose_output_loss: 0.0105 - emotion_output_loss: 0.0146 - gender_output_acc: 0.9977 - image_quality_output_acc: 0.9928 - age_output_acc: 0.9907 - weight_output_acc: 0.9949 - bag_output_acc: 0.9945 - footwear_output_acc: 0.9955 - pose_output_acc: 0.9962 - emotion_output_acc: 0.9951 - val_loss: 25.5894 - val_gender_output_loss: 1.8054 - val_image_quality_output_loss: 3.6503 - val_age_output_loss: 4.9215 - val_weight_output_loss: 3.3654 - val_bag_output_loss: 3.2996 - val_footwear_output_loss: 2.9502 - val_pose_output_loss: 2.1441 - val_emotion_output_loss: 3.4530 - val_gender_output_acc: 0.7560 - val_image_quality_output_acc: 0.4914 - val_age_output_acc: 0.3231 - val_weight_output_acc: 0.5711 - val_bag_output_acc: 0.5978 - val_footwear_output_acc: 0.6149 - val_pose_output_acc: 0.7434 - val_emotion_output_acc: 0.6341

Epoch 00047: val_loss did not improve from 7.01566
Epoch 48/50

Epoch 00048: LearningRateScheduler setting learning rate to 0.0001875821.
360/360 [==============================] - 92s 257ms/step - loss: 0.1289 - gender_output_loss: 0.0090 - image_quality_output_loss: 0.0190 - age_output_loss: 0.0277 - weight_output_loss: 0.0159 - bag_output_loss: 0.0223 - footwear_output_loss: 0.0115 - pose_output_loss: 0.0079 - emotion_output_loss: 0.0156 - gender_output_acc: 0.9969 - image_quality_output_acc: 0.9939 - age_output_acc: 0.9907 - weight_output_acc: 0.9948 - bag_output_acc: 0.9926 - footwear_output_acc: 0.9967 - pose_output_acc: 0.9976 - emotion_output_acc: 0.9947 - val_loss: 26.1574 - val_gender_output_loss: 1.8424 - val_image_quality_output_loss: 3.8523 - val_age_output_loss: 5.1229 - val_weight_output_loss: 3.4898 - val_bag_output_loss: 3.2600 - val_footwear_output_loss: 3.0198 - val_pose_output_loss: 2.2495 - val_emotion_output_loss: 3.3207 - val_gender_output_acc: 0.7676 - val_image_quality_output_acc: 0.4950 - val_age_output_acc: 0.3241 - val_weight_output_acc: 0.5756 - val_bag_output_acc: 0.5897 - val_footwear_output_acc: 0.6179 - val_pose_output_acc: 0.7394 - val_emotion_output_acc: 0.6164

Epoch 00048: val_loss did not improve from 7.01566
Epoch 49/50

Epoch 00049: LearningRateScheduler setting learning rate to 0.0001839137.
360/360 [==============================] - 93s 257ms/step - loss: 0.1003 - gender_output_loss: 0.0059 - image_quality_output_loss: 0.0172 - age_output_loss: 0.0227 - weight_output_loss: 0.0137 - bag_output_loss: 0.0114 - footwear_output_loss: 0.0111 - pose_output_loss: 0.0065 - emotion_output_loss: 0.0120 - gender_output_acc: 0.9982 - image_quality_output_acc: 0.9938 - age_output_acc: 0.9937 - weight_output_acc: 0.9956 - bag_output_acc: 0.9964 - footwear_output_acc: 0.9970 - pose_output_acc: 0.9977 - emotion_output_acc: 0.9966 - val_loss: 26.3959 - val_gender_output_loss: 1.7532 - val_image_quality_output_loss: 3.7073 - val_age_output_loss: 5.3950 - val_weight_output_loss: 3.5396 - val_bag_output_loss: 3.2626 - val_footwear_output_loss: 2.9505 - val_pose_output_loss: 2.1946 - val_emotion_output_loss: 3.5930 - val_gender_output_acc: 0.7742 - val_image_quality_output_acc: 0.4793 - val_age_output_acc: 0.3342 - val_weight_output_acc: 0.5746 - val_bag_output_acc: 0.6028 - val_footwear_output_acc: 0.6119 - val_pose_output_acc: 0.7434 - val_emotion_output_acc: 0.6517

Epoch 00049: val_loss did not improve from 7.01566
Epoch 50/50

Epoch 00050: LearningRateScheduler setting learning rate to 0.000180386.
360/360 [==============================] - 92s 257ms/step - loss: 0.0815 - gender_output_loss: 0.0040 - image_quality_output_loss: 0.0163 - age_output_loss: 0.0134 - weight_output_loss: 0.0130 - bag_output_loss: 0.0095 - footwear_output_loss: 0.0114 - pose_output_loss: 0.0054 - emotion_output_loss: 0.0086 - gender_output_acc: 0.9986 - image_quality_output_acc: 0.9939 - age_output_acc: 0.9953 - weight_output_acc: 0.9954 - bag_output_acc: 0.9967 - footwear_output_acc: 0.9970 - pose_output_acc: 0.9984 - emotion_output_acc: 0.9972 - val_loss: 27.6897 - val_gender_output_loss: 1.9109 - val_image_quality_output_loss: 3.8108 - val_age_output_loss: 5.5876 - val_weight_output_loss: 3.6486 - val_bag_output_loss: 3.6109 - val_footwear_output_loss: 3.2563 - val_pose_output_loss: 2.3652 - val_emotion_output_loss: 3.4994 - val_gender_output_acc: 0.7782 - val_image_quality_output_acc: 0.4738 - val_age_output_acc: 0.3508 - val_weight_output_acc: 0.5696 - val_bag_output_acc: 0.6038 - val_footwear_output_acc: 0.6220 - val_pose_output_acc: 0.7470 - val_emotion_output_acc: 0.6245

Epoch 00050: val_loss did not improve from 7.01566
Model took 4649.06 seconds to train
31/31 [==============================] - 5s 164ms/step
{'age_output_acc': 0.35080645161290325,
 'age_output_loss': 5.5875885563512,
 'bag_output_acc': 0.6038306451612904,
 'bag_output_loss': 3.610886966028521,
 'emotion_output_acc': 0.6244959677419355,
 'emotion_output_loss': 3.4993795118024273,
 'footwear_output_acc': 0.6219758064516129,
 'footwear_output_loss': 3.2563409651479414,
 'gender_output_acc': 0.7782258064516129,
 'gender_output_loss': 1.9108689062057003,
 'image_quality_output_acc': 0.4737903225806452,
 'image_quality_output_loss': 3.8108198412003054,
 'loss': 27.689685267786825,
 'pose_output_acc': 0.7469758064516129,
 'pose_output_loss': 2.3652066415356052,
 'weight_output_acc': 0.5695564516129032,
 'weight_output_loss': 3.648593471896264}
