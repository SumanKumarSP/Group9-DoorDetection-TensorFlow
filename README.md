# Group9-DoorDetection-TensorFlow

The project members are Diksha Bansal, Aparna Ningaraju Lnu and Suman Kumar Sanjeev Prasanna.

The present version uses TensorFlow to detect door object. The F-RCNN network is used on two CSUEB campus images for demonstration. The output i.e., successfully door detected image is shown on python using python plot.

This was tested on MAC with tensorflow installed using virtualenv.
The python version used is 3.6.3

additional dependencies
pip install moviepy

wget http://download.tensorflow.org/models/object_detection/faster_rcnn_inception_resnet_v2_atrous_oid_2017_11_08.tar.gz
tar -zxvf faster_rcnn_inception_resnet_v2_atrous_oid_2017_11_08.tar.gz

python doordetection.py
