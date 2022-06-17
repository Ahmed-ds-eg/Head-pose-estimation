# Head-pose-estimation
This Project uses machine learning algorithms to predict head position for human or animation 
## - Data used 
In this project we used AFLW2000 data which you can download from http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/Database/AFLW2000-3D.zip
this data contains dofferent pictures for human faces with different poses 
## - Environment setup 
In this project we used several libraries as follow 
- numpy 
- pandas 
- math 
- glob
- cv2 
- pathlib
- pandas 
- mediapipe
- sklearn 
## -Data preprocessing 
For our project Data are images and we will use these images for 
## - Model selection 
for this project we use SVR (support vector regression) with grid search algorithm 
## - Scoring 
We used mean square error as an evaluation metric for this project and results were as follow :
- Yaw   angle : mean square error was : 0.06442561907153023 
- Pitch angle : mean square error was : 0.08796355278108303
- Roll  anle  : mean square error was : 0.06848002050493925
