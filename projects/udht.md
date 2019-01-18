---
layout: project
type: project
image: images/DroneTechnologies.png
title: UH Drone Team
permalink: projects/udht
# All dates must be YYYY-MM-DD format!
date: 2018-07-01
labels:
  - Robotics
  - Raspberry Pi
  - Embedded Systems
  - Image Processing 
summary: A Vertically Integrated Project comprising of Mechanical, Electrical, and Computer Engineers building an autonomous drone for competition.
---

<div class="ui medium rounded images">
  <img class="ui image" src="../images/inflight.jpg">
  <img class="ui image" src="../images/plane.jpg">
</div>
The purpose of VIP UHDT Competition Team is to create an autonomous Unmanned Aerial System (UAS) and an autonomous Unmanned Ground Vehicle (UGV) that successfully performs all expected obligations of the 2019 Autonomous Unmanned Vehicle Systems International (AUVSI) Seafarer Student Unmanned Aerial System (SUAS) competition to a higher degree than that of last year’s system.


I was on the Image Processing team where there are 2 subsystems, image recognition and geo-tagging. Geo-tagging is the assignment of geo-location to an image once the telemetry data from the plane gets relayed to the ground station computer and processed. I will explain the process of our image processing below.


After UAV lands, Ground station downloads images stored in the Raspberry Pi. Tensorflow Object detection searches regions of interest in each image for a shape. Tensorflow alphanumeric recognition and OpenCV color recognition filter through false positives to identify target. Final targets are geotagged. Shape, color, and alphanumeric are written into .json file. The .json files and images of targets submitted to judges autonomously via Interoperability system





