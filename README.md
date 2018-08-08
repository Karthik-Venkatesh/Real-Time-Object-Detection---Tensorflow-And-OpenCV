# Real Time Object Detection - Tensorflow

Implemeting realtime object detection using Tensorflow api and OpenCV. For code explanation refer documentation in the `object_detection_tutorial.py` file.

## Download TensorFlow Model

Download the tensorflow model package from below link.

[TensorFlow - Models](https://github.com/tensorflow/models)

## Environment Set Up

Create conda environment using following command

	conda create -n myenv python=3
	
Activate environment 

	source activate myenv

## Installing Required Packages

Installing Open CV

	pip install opencv-python

The installation guide for tensorflow object detection is given in the following link. Make sure every steps are processed in installation.

[Tensorflow Object Detection - Package Installation Guide](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md)

## Running a program

1. Download **object\_detection\_tutorial.py** python file.
2. Move file to the Tensorflow models folder.
	file path is *models-master/research/object\_detection*
3. Run file using command `python object_detection_tutorial.py`
