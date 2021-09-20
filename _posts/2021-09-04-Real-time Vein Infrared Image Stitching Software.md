---
layout: post
topmost: false
title: Real-time Vein Infrared Image Stitching Software
categories: DesktopApp Python PyQt5 MySQL
description: Real-time Vein Infrared Image Stitching Software
keywords: DesktopApp
---

Time: Apr.2019 - Jun.2019 &emsp; Location: Wuhan, China

The real-time vein infrared image stitching software was established with Python and MySQL.

![@2x](/images/posts/python/image-stitching-software1.png){:height="70%" width="70%"}

The software adopts Threshold Segmentation and Background Subtraction to identify and extract effective light regions of infrared vein images from scanning videos, applies the ORB algorithm to match light region images and improves the stitched image using the Poisson fusion algorithm.

![@2x](/images/posts/python/image-stitching-software2.png){:height="70%" width="70%"}

During building this software, I considered the instability of the threshold segmentation algorithm. By using the skin model to narrow down the recognition scale, and adding Background Subtraction algorithms, I managed to enable the software to perform excellently under different circumstances.

I worked with another students to build this software and wrote over 3000 lines of code in Python. And we have coorperated with Wuhan Union Hospital to test the software and perfect it
