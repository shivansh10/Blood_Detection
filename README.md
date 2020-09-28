# Project of Blood Detection from an image

## Two approaches have been used i.e. :
### 1. Blood Detection through Convolutional Neural Network
### 2. Blood Detection through Haar Cascade Classifier


# 1. Blood Detection through CNN:

   The model is Sequential model. The trained network predicts whether the input image does have blood or not. The model is saved which can be used for opencv arena.

   The dataset library should be like:
   <pre>  
   dataset: <br />
          train_set: <br />
                    blood <br />
                          blood1.png <br />
                          blood2.png <br />
                          blood3.png <br />
                          . <br />
                          . <br />
                    noblood <br />
                          noblood1.png <br />
                          noblood2.png <br />
                          noblood3.png <br />
                          . <br />
                          . <br />
             test_set: <br />
                    blood <br />
                          blood1.png <br />
                          . <br />
                          . <br />
                    noblood <br />
                          noblood1.png <br />
                          . <br />
                          . <br />
     </pre>                      
   To see in more descriptive way, run -   [blood_noblood_detection_cnn.ipynb](detection_cnn/blood_noblood_detection_cnn.ipynb)


# 2. Blood Detection through Haar Cascade Classifier:

   The pretrained model for face detection is used which is present in cv2 library. Then on the face detected image, the labels in been set according to the name of the file. Then through basic python using computer vision tools, The blood face is been detected through this way.  <br />
   The dataset library should be like: 
   
  <pre>  
  dataset:<br /> 
          train_set:<br />
                    b1<br />
                          blood1.png<br />
                          blood2.png<br />
                          blood3.png<br />
                          .<br />
                          .<br />
                    b2<br />
                          noblood1.png<br />
                          noblood2.png<br />
                          noblood3.png<br />
                          .<br />
                          .<br />
             test_set:<br />
                    blood<br />
                          blood1.png<br />
                          .<br />
                          .<br />
                    noblood<br />
                          noblood1.png<br />
                          .<br />
                          .<br />
   </pre>                       
  To see in more descriptive way, run -    [blood_noblood_detection_haarcascade.ipynb](detection_haarcascade/blood_noblood_detection_haarcascade.ipynb)
                          
               
