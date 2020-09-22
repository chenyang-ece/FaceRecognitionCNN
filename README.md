# FaceRecognitionCNN
The model in this design is the enhanced version of LeNet. Please use the algorithm as follows:  
First, download the dataset we need and unzip it to directory 'img_source', and then run [set_other_faces.py]    
Second, prepare a training video of user's face or just use camera to collect user's face data, run [get_my_faces.py]  
Third, run [train_faces.py] to train the cnn model, some parameters can be adjust in this file  (learning rate and batch size )  
Last, run [is_my_faces] to verify the proformance of the model  
  
  
Coding Environment  
Python: 3.5  
Compiler: Pycharm Community Edition 2020  
Tensorflow	1.10  cpu  
Opencv	3.42  
Dlib	18.18  
Numpy	3.42  
Scikit-Learn	0.20  
Code site: https://github.com/chenyangece/FaceRecognitionCNN  

