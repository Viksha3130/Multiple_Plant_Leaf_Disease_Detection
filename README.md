# Multiple_Plant_Leaf_Disease_Detection

Yolov5 is the fastest and most accurate object detection model
https://github.com/ultralytics/yolov5.git

## Steps

1)  Collect the Dataset and Annotate the image  with labelmg Annotation Tool   
https://github.com/tzutalin/labelImg


2)  Train the model (yolov5.ipynb)

3) Run the Detect.py file

         python detect.py --source object_detection_images --weights runs/train/exp/weights/last.pt --img 800 --save-txt --save-conf
