# Head_Pose_Estimation-

## First Thing:
#### 1- preparing data for model training ( we used MediaPipe and CV2 libraries for extracting points and for face detection from pictures).
#### 2- splited the data to training and testing.
#### 3- used Random forstet regressors.

## Second Thing:
#### 1- we have read the video and converting it to frames. 
#### 2- for each frame, we extracted the points and predicted the 3 position axis (pitch,yaw,roll) and drew it on each frame.
#### 3- finaly, we converted the frames to video again.


## Reference : 
##### https://google.github.io/mediapipe/solutions/face_mesh.html
##### http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/Database/AFLW2000-3D.zip
