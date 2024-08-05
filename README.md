# object_detection-using-YOLOV4_TINY
YOLOv4-tiny is the compressed version of YOLOv4 designed to train on machines that have less computing power
The tiny and fast version of YOLOv4 - good for training and deployment on limited compute resources, and getting a feel for your dataset

FOR TRAINING
I performed detection on the vehicles, by detection the vehicle class. for this I used an annotated data of arounf 1400 vehicles and then trained my model with the same data. The tool which I preffered for the annotation was ROBOFLOW.   

FOR DARKNET
clone the git repo of ALEXEYAB
Their you will get the folder of data and congiguration. Make changes to your configuration file according to your no of classes.  the formula for the 
MAX_BATCH = 2000(NO OF CLASS)
USE 6000 IF NO OF CLASS IS 1 OR 2 OR 3

NO OF FILTERS= (CLASSES+5)*3
STEPS = 90% OF MAX_BATCH, 80% OF MAX_BATCH
