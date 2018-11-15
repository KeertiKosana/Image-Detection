# Image-Detection
More information on: https://pjreddie.com/darknet/yolo/

git clone https://github.com/pjreddie/darknet
cd darknet
make

Get pre-trained weights: wget https://pjreddie.com/media/files/yolov3.weights
Run detector using a sample image from the directory /darknet/: ./darknet detect cfg/yolov3.cfg yolov3.weights data/dog.jpg

