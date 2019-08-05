---
title: "Robotic Human Palm Replication"
excerpt: "Designed a working model of a human palm which replicated the palm motion and controls using a video feed of a human palm
through a web-cam.<br/> [Github](https://github.com/mchandak29/robotic-palm)
<br/><img src='/images/Hardware_Design.png' width='350' height='350'>"
collection: portfolio
---

The project goal was to design a working model of a human palm and to replicate the palm motion and controls using a video feed of 
a human palm using cameras.The design consists of four fingers and a thumb attached on a palm base. Eachfinger consists of three 
smaller components, and the thumb is made of two components, similar to a real human palm. All the fingers have a string making a
loop within each finger and connecting all these smaller components, while the other end of the string goes around a motor. Each of 
the four fingers are connected to a motor each. The thumb is connected to two motors giving it two degrees of freedom. All the 
motors are controlled by an Arduino. We achieved pose estimation using a three stage convolutional pose
machines(CPMs) built on tensorflow-python and kalman filters resulting in higher resolution and accuracy.<br/>

## Results
<img src='/images/Screenshot%20from%202019-08-02%2015-40-24.png' width='480'><br/>
[Github](https://github.com/mchandak29/robotic-palm)
