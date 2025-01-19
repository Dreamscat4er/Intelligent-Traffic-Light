Raspberry Pi 4 and MATLAB software was used to build the smart traffic controller.

#How it works
The detection part of the system involves several steps, including removing noise and retrieving information to calculate the number of cars detected. 
The system then switches traffic lights based on the detected car count. The MATLAB Image Acquisition and Computer Vision toolboxes were used to obtain 
and analyze the video frames received from the connected cameras. The detector uses the Gaussian Mixture Model to suppress frequently occurring features 
and to detect abnormal features, which are then used to detect changes caused by moving objects. Morphological operations are used to remove noise 
from the output. Finally, the system counts the cars detected by the Foreground Detector and switches the traffic lights accordingly. 
