dependencies:
Python3

numpy :
	use : pip install numpy
opencv-python: 
	use: pip install opencv-python
argparse:
	use: pip install argparse


download this file , which is the training file:
     https://pjreddie.com/media/files/yolov3.weights

excuting:
download whatevery image on internet, or take a pic with your devices, and copy it into the project directory, and run

python yolo_opencv.py --image img.jpg --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt

where img.jpg is the image we want to find objects within it, change this to your images name.