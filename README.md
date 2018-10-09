# YOLO-Algorithm
You are working on a self-driving car. As a critical component of this project, you'd like to first build a car detection system. To collect data, you've mounted a camera to the hood (meaning the front) of the car, which takes pictures of the road ahead every few seconds while you drive around.

YOLOv2
YOLO ("you only look once") is a popular algoritm because it achieves high accuracy while also being able to run in real-time. This algorithm "only looks once" at the image in the sense that it requires only one forward propagation pass through the network to make predictions. After non-max suppression, it then outputs recognized objects together with the bounding boxes.

The actual car detection model is very computationally expensive to train, therefore I load the pre-trained weights in the model (the pre-trained model is from Drive.AI) and	wrote YOLOv2 algorithm to construct 5 anchor boxes per photo for car detection based on a pre-trained deep CNN. I also Implemented threshold filtering and non-max suppression for anchor box optimization.

