# Project: Deep Drowsiness Detection using YOLO, Pytorch and Python
credit for learning the project is to https://github.com/nicknochnack/YOLO-Drowsiness-Detection/blob/main/Drowsiness Detection Tutorial.ipynb 

Here is a project using the Deep Learning algorithms of Pytorch with the YOLO of the version 5 model in implementing real-time object detection. Here I am testing it on a use case of detecting the drowsiness state of an individual. 

In this Jupyter notebook, I will be implanting the use case following those steps: 
1. Install and Import Dependencies
2. Cloning the Ultralytics YOLOv5 repository
3. Load the Model of Yolo V5 
4. Initial Testing of the pre-trained (on COCO labels) Model by making Detections with Images
5. Initial Testing on Pre-Recorded Videos but this time on Real-Time Detections
6. Creating New Custom Images to be used later to Custom (Fine-Tune) Train the Model   
7. Label the New Images Using the LabelImg App
8. Fine-Tuning the Model on Custom Labels/Classes
9. Load the trained ‘Drowsiness” Model 
10. Perform Drowsiness Detection on A Single Image
11. Perform Drowsiness Detection on Real-Time Video
