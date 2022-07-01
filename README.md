# Logo Detection

This repository containes the code for the **Logo Detection** in Video Project

## OCI AI Vision to detect a logo

In this demo OCI AI Vision Service is used to detect the presence of a logo inside a Video

## Tools used

* OpenCV (cv2)
* OCI AI Vision Service, for Object Detection
* OCI Data Labelling Service (DLS)

## Data Labelling

Around 140 images, stored in a bucket in the Object Storage, have been labelled using OCI DLS

## ML Model

OCI AI Vision has been used. A model has been trained on the labelled dataset for 8 hrs.

## Metrics from the Model

|Metric.  | Value |
|---------|-------|
|mAP@0.5  | 0.9038|
|Precision| 0.9886|
|Recall   | 0.8978|

## Demo

The main NoteBook for the demo is [here](https://github.com/luigisaetta/logo_detection/blob/main/analyze_video3_rp.ipynb) 

To simplify the code using OCI AI Vision SDK, a Python class has beeen provide. See: [oci_vision_utilities](https://github.com/luigisaetta/logo_detection/blob/main/oci_vision_utilities.py)






