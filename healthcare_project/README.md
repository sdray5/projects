The dataset comes from here:https://echonet.github.io/dynamic/index.html#dataset

The goal of the project is to classify ejection fraction based on echocardiogram videos as being normal (between 55 and 75) or abnormal (outside that range).
To accomplish this, I first created a segmentation model for the left ventricle of the heart.
After that, I shaded the predicted pixels blue and fed that image into the classification model.

The files should be run in this order: 
EchoNet Dynamic segmentation preprocessing  -> EchoNet Dynamic segmentation model -> EchoNet Dynamic Coloring Frames -> EchoNet Dynamic 3D CNN 2 Class Classification
