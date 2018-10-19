# tf_shark_detector_colab
TensorFlow Object Detection API using Google Colab

## Introduction
Apply [Tensorflow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection) pre-trained model for custom dataset. In this project, we support the [Shark Pulse project](http://baseline3.stanford.edu/SharkPulse/) led by Stanford researchers at Hopkins Marine Station. We labelled 200 shark images with [labelImg toolkit](https://github.com/tzutalin/labelImg), by drawing bounding boxes around the sharks. Then trained with TensorFlow Object Detection model to detect sharks in the images. This shark detector serves as image collector for Shark Pulse project that aims to establish shark species baseline for reseearch and conservation purposes.

## Code
See Colab (Jupyter) notebooks for more details. One is for training, building inferences; one is for making predictions and detect shark in the videos and crop the bounding boxes. The scripts can be used for other custom image datasets. Google Colab provides free GPU resources!

## Pre-trained model
We utilized Faster R-CNN pre-trained on inception_v2 COCO dataset (2018/01/28).

## Requirements
- Python 2
- TensorFlow 1.2
(already installed with Google Colab environment)
