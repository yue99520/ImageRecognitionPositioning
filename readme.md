# Yolo Detection Adapter Tool
This small project is in dev-stage now.
Enjoy and welcome for PR :)

## Intro
This tool can simply run yolo and return a result witch is containing objects' information(like position(xy), width and height...). 
 
## Preparing
You can clone this project in the directory of darknet(yolo).
The Controller.py's path is: "yolo_detector_tool/Controller.py"
You can put it in another directory and try running.
Don't forget to install dependency cv2

## Configuration
The configuration of weights, names, img, cfg file is in the Controller.py.
Controller can be considered as a demo, you can reprogram it into your own version.

## Run
Run ```python Controller.py```