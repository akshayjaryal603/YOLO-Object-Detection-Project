# YOLO-Object-Detection-Project
YOLOv3 is very regressed model for Object detection supported for both image and video detection.

The yolov3 models are taken from the official yolov3 paper which was released in 2018. 
The yolov3 implementation is from [darknet](https://github.com/pjreddie/darknet). Also, this project implements an option to perform classification real-time using the webcam.

Install all the necessary libraries

Run "yolo.py" file

This project support object detection for image and video both.
Change the video path inside the yolo.py file or pass it as a command line argument 
python yolo.py --image-path='/path/to/image/'

To infer real-time on webcam:-
python "yolo.py"
