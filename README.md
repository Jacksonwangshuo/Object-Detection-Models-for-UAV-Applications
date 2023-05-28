# Object-Detection-Models-for-UAV-Applications

OpenCV dnn module supports running inference on pre-trained deep learning models from popular frameworks like Caffe, Torch and TensorFlow.

When it comes to object detection, popular detection frameworks are
YOLO
SSD
Faster R-CNN
Support for running YOLO/DarkNet has been added to OpenCV dnn module recently.

# YOLO (You Only Look Once)
Download the pre-trained YOLO v3 weights file from this link and place it in the current directory or you can directly download to the current directory in terminal using

$ wget https://pjreddie.com/media/files/yolov3.weights

Provided all the files are in the current directory, below command will apply object detection on the input image dog.jpg.

$ python yolo_opencv.py --image dog.jpg --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt

Command format

$ python yolo_opencv.py --image /path/to/input/image --config /path/to/config/file --weights /path/to/weights/file --classes /path/to/classes/file


# XTDrone Simulation Platform:
https://toscode.gitee.com/sihaitangzhu/XTDrone/
