---
title:  "Yawn Detector"
date:   2019-07-13 20:00:00
categories: [Projects]
tags: [Projects]
---
<b><font size = "5">Yawn Detector</font></b>

<font size = "3">

<p>Deep Learning Based Yawn Detection for Driver Drowsiness Prediction</p>

<p>This project is meant to detect whether the user is yawning or not given a live video feed</p>

<p>I worked along my teammate <b>Shubhad Mathur</b> to accomplish this task in real-time. </p>

<p>We started off by doing some online courses on deep learning. 

When we had a good grasp on DL concepts, we read some research papers which helped us to get familiar with the state-of-art techniques which have already been employed for yawn detection. 

With the help of our mentor, we then finalised the architecture of the yawn detection model. We then used the OpenCV and DLIB libraries for mouth detection, created a CNN model for mouth features extraction and then implemented a bi-LSTM for the final yawn detection. 

We used YawDD and NTHU-DDD datasets for training and testing. 

We then tested our model on live videos and tweaked the hyperparameters a bit to get the maximum possible accuracy.</p>

<p>The final model did work in real-time (~27 fps)</p>

<p><a href ="https://github.com/iCoder0020/DL-based-Yawn-Detection">Here</a> is a link (currently private; will be updated soon) to our repository which contains the files corresponding to the project.</p>

</font>