Raspberry Pi 4 and MATLAB software was used to build the smart traffic controller. (December 2022)

#How it works

The detection part of the system involves several steps, including removing noise and retrieving information to calculate the number of cars detected. 
The system then switches traffic lights based on the detected car count. The MATLAB Image Acquisition and Computer Vision toolboxes were used to obtain 
and analyze the video frames received from the connected cameras. The detector uses the Gaussian Mixture Model to suppress frequently occurring features 
and to detect abnormal features, which are then used to detect changes caused by moving objects. Morphological operations are used to remove noise 
from the output. Finally, the system counts the cars detected by the Foreground Detector and switches the traffic lights accordingly. 

#Mockup overview

![image](https://github.com/user-attachments/assets/b04f435b-00cf-4063-af6c-d55acd7ae761)

#Object capture

![image](https://github.com/user-attachments/assets/7f8eb59e-db55-4f5b-9177-89e50c9cd276)

#Removing background

![image](https://github.com/user-attachments/assets/f671766c-7438-4bc7-8566-4e3188dee241)

#System architecture

![image](https://github.com/user-attachments/assets/a2e5ccb3-bcce-42b8-96d8-66e32d1aa8bb)




