#Object-Detection---Yolo-OpenCV#

#Support for running YOLO/DarkNet on OpenCV
pip install numpy opencv-python

#Download the pre-trained YOLO v3 weights file in current directory using terminal command
wget https://pjreddie.com/media/files/yolov3.weights or  download from https://pjreddie.com/media/files/yolov3.weights

#Command to run python script in current directory where all the files - yolo config, classes text , input image are kept
!python yolo_opencv.py --image dog.jpg --config yolov3.cfg --weights E:/object_detection/yolov3.weights (path to weight file in my windows) --classes yolov3.txt

An output image named object-detection.jpg is created. 
