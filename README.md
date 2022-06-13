# FaceMaskDetection
Made a face mask detection model on Python using Machine Learning, which was able to identify if a person was wearing a face mask or not. This project was created on Jupyter Notebook.

## Table of Contents
* [Motivation](#Motivation)
* [Dataset](#Dataset)
* [Methodology](#Methodology)

## Motivation
With the covid-19 virus wreaking havoc across the world, destroying lives and livelihood, various measures have been adopted by the government to mitigate the spread of the virus, one of them include face masks. Face masks are one of the most potent weapons against the spread of the virus. We wanted to play our part in the fight against this virus by implementing a face mask detection algorithm, which will allow governments and other authorities to effectively enforce mask mandates among the people, thus minimizing the spread of the virus and achieving an essential step in protecting our communities from this deadly virus.

## Dataset
The dataset has 690 images "with masks" and 686 images "without masks". Click [here](https://drive.google.com/uc?export=download&id=1m6Rd5nxol_cT2EKHSodli9HD1L6k0bKR) to download the dataset.

## Methodology
Developed the model using techniques of Transfer Learning from the MobileNetV2 architecture and used TensorFlow, Keras, NumPy, OpenCV libraries. 
First trained the model using the "imagenet" dataset and then fine-tuned the model to detect whether a person was wearing a facemask or not.
