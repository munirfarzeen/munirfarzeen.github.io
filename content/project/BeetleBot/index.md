---
title: BeetleBot
summary:
tags:
  - Deep Learning
  - Indoor Robotics
  - ROS
  - Obsctale Avoidance

date: '2022-02-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---



The recent development in the field of mobile robotics has made them available for commercial and research  purposes.  The  primary  challenges  that  are  encountered  by  deploying  the  mobile  robot  in  a dynamic environment is mapping and navigation. Simultaneous localization and mapping (SLAM) provide a good understanding of the environment for navigation and path planning. In this work, we explore the problem  of  mapping  and  navigation  by  incorporating  the  semantics  of  the  environment.  For  the experimental  setup,  a  robot  (BeetleBot)  is  designed  having  equipped  with  Kobuki  mobile  base, Realsense  RGB-D  camera,  range  sensors  and  NVidia  Jetson  Xavier  as  computation  computer.  The autonomous semantic mapping and navigation are performed using RTAB-MAP with the inclusion of A* algorithm for exploring and updating the unknown environment and deep learning-based object detection algorithm. A Proportional-Integral-Derivative (PID) is implemented as a controller for the BeetleBOT. We have used the Robot Operating System (ROS) as a software development platform for the BeetleBOT. The experimental evaluation shows the mapping and localization efficacy using the BeetleBOT as our mobile robot. 

{{< figure src="turtlebot.png" caption="Overall architecture of BeetleBot using ROS framework." numbered="true" >}}



The demonstration video of the project.

{{< video src="robot navigation 2.mp4" controls="yes" >}}
{{< video src="video_2021-11-01_01-05-52.mp4" controls="yes" >}}



