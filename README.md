# Project of Blood Detection from an image

## Two approaches have been used i.e. :
### 1. Blood Detection through Convolutional Neural Network
### 2. Blood Detection through Haar Cascade Classifier


# 1. Blood Detection through CNN:

   The model is Sequential model. The trained network predicts whether the input image does have blood or not. The model is saved which can be used for opencv arena.

   The dataset library should be like:
   
   dataset:
          train_set:
                    blood
                          blood1.png
                          blood2.png
                          blood3.png
                          .
                          .
                    noblood
                          noblood1.png
                          noblood2.png
                          noblood3.png
                          .
                          .
             test_set:
                    blood
                          blood1.png
                          .
                          .
                    noblood
                          noblood1.png
                          .
                          .
                          
      To see in more descriptive way, run -    detection_cnn/blood_noblood_detection_cnn.ipynb


# 2. Blood Detection through Haar Cascade Classifier:

   The pretrained model for face detection is used which is present in cv2 library. Then on the face detected image, the labels in been set according to the name of the file. Then through basic python using computer vision tools, The blood face is been detected through this way. 
   The dataset library should be like:
   
   dataset:
          train_set:
                    b1
                          blood1.png
                          blood2.png
                          blood3.png
                          .
                          .
                    b2
                          noblood1.png
                          noblood2.png
                          noblood3.png
                          .
                          .
             test_set:
                    blood
                          blood1.png
                          .
                          .
                    noblood
                          noblood1.png
                          .
                          .
                          
  To see in more descriptive way, run -    detection_haarcascade/blood_noblood_detection_haarcascade.ipynb
                          
               
