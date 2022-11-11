# NBA-Score-Detection

This is a basketball score detection system as a coursework in undergrad Computer Vision

The score detection task is completed based on an object detector which locates the basket and a classifier to recognize it as ( *left-made-basket/right-made-basket/left-empty-basket/right-empty-basket* ). Video score detection is completed on the level of a rule-based approach.

Note the model only attend to 1pt/2pt

## Model

The dataset is small-scale and handcrafted from several NBA video games.

The task of object detection is based upon a Yolov3 pretrained network.

Apart from yolo, a separate binary classifier is also designed to refine the basket detection.

![](images/pipeline.png)

## Demo

This is a live demo video

![](images/demo.gif)
