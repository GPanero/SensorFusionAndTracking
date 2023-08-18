# Sensor Fusion and Object Tracking
Self-Driving Car Engineer Nanodegree<br/>
https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013

## Installation Instructions

Download or clone this github repository with the starter code:
https://github.com/udacity/nd013-c2-fusion-starter

Follow all the installation instructions in the github repository:
https://github.com/udacity/nd013-c2-fusion-starter#installation-instructions-for-running-locally

Basically, you need to install Python 3.7 and all the requirements in the file `requirements.txt` by typing this command in the terminal: `pip3 install -r requirements.txt`.

Additionally, you need to download and install the "Waymo Open Dataset Files" and the Pre-Trained Models for `darknet` <https://drive.google.com/file/d/1Pqx7sShlqKSGmvshTYbNDcUEYyZwfn3A/view?usp=sharing> and `fpn_resnet` <https://drive.google.com/file/d/1RcEfUIF1pzDZco8PJkZ10OL-wLL2usEj/view?usp=sharing>. Once downloaded, please copy the model files into the paths `/tools/objdet_models/darknet/pretrained` and `/tools/objdet_models/fpn_resnet/pretrained` respectively.

Moreover, download the precomputed results for `darknet` and `fpn_resnet` in this link <https://drive.google.com/drive/folders/1-s46dKSrtx8rrNwnObGbly2nO3i4D7r7?usp=sharing>. And then unzip them into the folder `/results`.

Once you completed the first steps to install this project, it is time to download the following files in this github repository and to copy them in the following directories:

| FILES TO COPY | DIRECTORIES |
| ------------- | -------------|
| [`/student/loop_over_dataset.py`](/student/loop_over_dataset.py) | `/` |
| [`/student/association.py`](/student/association.py) | `/student/` |
| [`/student/filter.py`](/student/filter.py) | `/student/` |
| [`/student/measurements.py`](/student/measurements.py) | `/student/` |
| [`/student/trackmanagement.py`](/student/trackmanagement.py) | `/student/` |
| [`/student/objdet_detect.py`](/student/objdet_detect.py) | `/student/` |
| [`/student/params.py`](/student/params.py) | `/misc/` |
| [`/student/evaluation.py`](/student/evaluation.py) | `/misc/` |

Note: The directory `/` is relative to this project's directory.

Now that you have successfully installed this project, you can run it by using this command `python loop_over_dataset_f4.py`.

## External Dependencies
Parts of this project are based on the following repositories:

Simple Waymo Open Dataset Reader
Super Fast and Accurate 3D Object Detection based on 3D LiDAR Point Clouds
Complex-YOLO: Real-time 3D Object Detection on Point Clouds
