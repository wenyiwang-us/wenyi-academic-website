---
title: Immersive and Intelligent Humanoid Robot Control System
summary: We have built a complete robot control system without big, heavy wearables. We control our robot by standing in front of MS Kinect v2. We also integrated VR and object detection technologies to make our robot system intelligent, so the robot operator will have an immersive experience while controlling and playing with our system.
tags:
- Machine Learning
- Windows Development
- Android Development
- Systems
- Computer Vision
- Robotics
date: "2018-09-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: university
  icon_pack: fas
  name: Northeastern University, China
  url: http://english.neu.edu.cn/
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
We have built a complete robot control system that does not require big and heavy wearable in order to acquire operator's movement. 
Instead, we integrated MS Kinect v2 into our system for recognizing operator's movement. The movement recognize by Kinect is noisy, so we developed a dedicated filter module to smooth the signals.
To let the operator have an immersive experience and see what the robot can see, we also integrated VR technology. 
On our VR device, the operator can see the real-time video capture stream from the robot's camera. They can also move their head to see around.

To make our system intelligent, we developed an algorithm that enable our robot to guess an undetected object's location in a realtime video frame.
If we want the robot to find an object, it can always provide hint on where the object will be most likely to appear.


